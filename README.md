<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

    <link rel="stylesheet" href="css.css">
    <style>
        body {
            background-color: #f8f9fa;
        }
        
        .modal-content {
            border-radius: 10px;
            padding: 20px;
        }
        
        .btn-custom {
            background-color: #4A4A4A;
            color: white;
            width: 100%;
        }
        
        .btn-custom:hover {
            background-color: #333;
        }
        
        .btn-outline-custom {
            border: 1px solid #4A4A4A;
            color: #4A4A4A;
            width: 100%;
        }
        
        .btn-outline-custom:hover {
            background-color: #f8f9fa;
        }
    </style>
</head>

<body>
    <section class="header">
        <div class="container py-3">
            <div class="row d0">
                <div class="col-md-3 ">
                    <img src="logo.svg" class="img-fluid" alt="Logo">
                </div>
                <div class="col-md-4 py-4">
                    <div class="input-group mb-3">
                        <input type="text" class="form-control" placeholder="Tìm kiếm" aria-label="Tìm kiếm" aria-describedby="basic-addon2">
                        <span class="input-group-text" id="basic-addon2"><i class="fa-solid fa-magnifying-glass"></i></span>

                    </div>
                </div>
                <div class="col-md-3 py-4">
                    <div class="row">
                        <div class="col">
                            <div class="col-8 text-warning" data-bs-toggle="modal" data-bs-target="#registerModal"><i class="fa-regular fa-user"></i>Đăng ký</div>
                        </div>
                        <div class="modal fade" id="registerModal">
                            <div class="modal-dialog">
                                <div class="modal-content">
                                    <div class="modal-header">
                                        <p class="modal-title fs-5 fw-bold">Tạo tài khoản mới</p>
                                        <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
                                    </div>
                                    <div class="modal-body">
                                        <form>
                                            <div class="mb-3">
                                                <label class="form-label">Họ và Tên</label>
                                                <input type="text" class="form-control" placeholder="Nhập họ và tên">
                                            </div>
                                            <div class="mb-3">
                                                <label class="form-label">Số điện thoại</label>
                                                <input type="text" class="form-control" placeholder="Nhập số điện thoại">
                                            </div>
                                            <div class="mb-3">
                                                <label class="form-label">Email</label>
                                                <input type="email" class="form-control" placeholder="Nhập email">
                                            </div>
                                            <div class="mb-3">
                                                <label class="form-label">Mật khẩu</label>
                                                <input type="password" class="form-control" placeholder="Nhập mật khẩu">
                                            </div>
                                            <div class="mb-3">
                                                <label class="form-label">Xác nhận mật khẩu</label>
                                                <input type="password" class="form-control" placeholder="Nhập lại mật khẩu">
                                            </div>
                                            <button type="submit" class="btn btn-dark w-100">Đăng ký</button>
                                        </form>

                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col">
                            <div class="col-8 text-warning" data-bs-toggle="modal" data-bs-target="#loginModal"><i class="fa-sharp fa-solid fa-user"></i>Đăng nhập</div>
                        </div>
                        <div class="modal fade" id="loginModal">
                            <div class="modal-dialog">
                                <div class="modal-content">
                                    <div class="modal-header">
                                        <p class="modal-title fs-5 fw-bold">Cocoon chào bạn trở lại</p>
                                        <button type="button" class="btn-close" data-bs-dismiss="modal"></button>
                                    </div>
                                    <div class="modal-body">
                                        <form>
                                            <div class="mb-3">
                                                <label class="form-label">Số điện thoại</label>
                                                <input type="text" class="form-control" placeholder="Nhập số điện thoại">
                                            </div>
                                            <div class="mb-3">
                                                <label class="form-label">Mật khẩu</label>
                                                <input type="password" class="form-control" placeholder="Nhập mật khẩu">
                                            </div>

                                            <button type="submit" class="btn btn-dark w-100">Đăng nhập</button>
                                        </form>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
                <div class="col-md-2 py-4">
                    <a href="#" class="position-relative">
                        <span class="fs-5"><i class="fa-sharp fa-solid fa-cart-shopping" data-bs-target="#cartModal" data-bs-toggle="modal"></i></span>
                        <span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">
                          0                     
                        </span>
                    </a>
                    <div class="modal fade" id="cartModal" tabindex="-1" aria-labelledby="cartModalLabel" aria-hidden="true">
                        <div class="modal-dialog">
                            <div class="modal-content">
                                <div class="modal-header">
                                    <p class="modal-title fs-5 fw-bold" id="cartModalLabel">Giỏ hàng của bạn</p>
                                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Đóng"></button>
                                </div>
                                <div class="modal-body">
                                    <form>
                                        <div class="mb-3">
                                            <img src="moi3.jpg" width="100">
                                            <label class="form-label fw-semibold">Sửa rửa mặt sen hậu giang</label>
                                            <div class="d-flex justify-content-between align-items-center mb-2">
                                                <div>Số lượng: 1</div>
                                                <div>138,000₫</div>
                                            </div>
                                        </div>
                                        <div class="mb-3">
                                            <img src="moi5.jpg" width="100">
                                            <label class="form-label fw-semibold">Sáp dưỡng ẩm đa năng sen Hậu Giang Cocoon</label>
                                            <div class="d-flex justify-content-between align-items-center mb-2">
                                                <div>Số lượng: 1</div>
                                                <div>178,000₫</div>
                                            </div>
                                        </div>

                                        <div class="d-flex justify-content-between border-top pt-3 mt-3">
                                            <strong>Tổng tiền:</strong>
                                            <strong class="text-danger">350,000₫</strong>
                                        </div>

                                        <button type="button" class="btn btn-dark w-100 mt-4">Thanh toán</button>
                                    </form>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>
    <section class="menu bg-warning">
        <div class="container ">
            <div class="row">
                <div class="col-md-3"></div>
                <div class="col-md-9">
                    <nav class="navbar navbar-expand-lg bg-warning ">
                        <div class="container-fluid">
                            <a class="navbar-brand d-none" href="#">Navbar</a>
                            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                      </button>
                            <div class="collapse navbar-collapse " id="navbarSupportedContent">
                                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                                    <li class="nav-item">
                                        <a class="nav-link text-white active" aria-current="page" href="trangchu1.html">Trang chủ</a>
                                    </li>
                                    <li class="nav-item">
                                        <a class="nav-link text-white" href="gioithieu.html">Giới thiệu</a>
                                    </li>
                                    <li class="nav-item dropdown">
                                        <a class="nav-link text-white dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                                            Sản phẩm
                                        </a>
                                        <ul class="dropdown-menu ">
                                            <li><a class="dropdown-item" href="damat.html">Chăm Sóc Da Mặt</a></li>
                                            <li><a class="dropdown-item" href="toc.html">Chăm Sóc Tóc</a></li>

                                            <li><a class="dropdown-item" href="cothe.html">Chăm Sóc Cơ Thể</a></li>
                                            <li><a class="dropdown-item" href="moi.html">Dưỡng Môi</a></li>
                                        </ul>
                                    </li>
                                    <li class="nav-item">
                                        <a class="nav-link text-white " aria-disabled="true" href="lienhe.html">Liên hệ</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </nav>
                </div>
            </div>
        </div>
    </section>
    <section class="content my-0 ">
        <div class="container-fluid mt-0">
            <div class="row ">
                <div class="col-md-3 d3">
                    <section class="">
                        <section class="certification-section">
                            <div class="container ">
                                <p class="fw-bold fs-3 mt-4">CHỨNG NHẬN BỞI CÁC TỔ CHỨC QUỐC TẾ</p>
                                <div class="row justify-content-center">
                                    <div class="col-md-10 mb-5">
                                        <img src="leaping_bunny_bdcbdfe9f1.svg" width="300">
                                        <div class="cert-title fs-2">Leaping Bunny</div>
                                        <div class="cert-subtitle fs-6">Chương trình Leaping Bunny</div>
                                        <div class="cert-description fs-5">
                                            Chứng nhận Leaping Bunny của tổ chức Cruelty Free International là cam kết không thử nghiệm trên động vật cho sản phẩm cũng như thành phần.
                                        </div>
                                        <img src="o.svg" width="300">
                                        <div class="cert-title fs-2">The Vegan Society</div>
                                        <div class="cert-subtitle fs-6">Hiệp hội Thuần chay Quốc tế</div>
                                        <div class="cert-description fs-5">
                                            Vegan Society chứng nhận sản phẩm không chứa thành phần động vật và không thử nghiệm trên động vật.
                                        </div>
                                        <img src="o1.svg" width="300">
                                        <div class="cert-title fs-2">PETA</div>
                                        <div class="cert-subtitle fs-6">Animal Test-Free & Vegan</div>
                                        <div class="cert-description fs-5">
                                            Chương trình của PETA xác nhận sản phẩm không thử nghiệm trên động vật và không chứa thành phần có nguồn gốc động vật.
                                        </div>
                                        <br>
                                        <div>
                                            <img src="o2.jpg" width="270">
                                            <p class="fw-bold">Chương trình cùng Cocoon sống xanh mỗi ngày.</p>
                                        </div>
                                        <br>
                                        <div>
                                            <img src="o3.jpg" width="270">
                                            <p class="fw-bold">Ửng hồng không ửng đỏ-Chung tay chăm sóc trẻ em vùng cao.</p>
                                        </div>
                                        <br>
                                        <div>
                                            <img src="o4.jpg" width="270">
                                            <p class="fw-bold">Chung tay cứu trợ chó mèo lang thang cùng Tổ chức Động vật Châu á.</p>
                                        </div><br>
                                        <div>
                                            <img src="v1.jpg" width="270">
                                            <img src="vn.jpg" width="270"><br>
                                            <p class="fw-bold fs-4 text-warning">CHÀO MỪNG ĐẠI LỄ 50 NĂM GIẢI PHÓNG MIỀN NAM </p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </section>
                    </section>
                </div>
                <div class="col-md-9">
                    <section class="content my-0">
                        <div class="container ">
                            <div class="d4">
                                <div class="slider">
                                    <div id="carouselExampleIndicators" class="carousel slide">
                                        <div class="carousel-indicators">
                                            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                                            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                                            <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
                                        </div>
                                        <div class="carousel-inner">
                                            <div class="carousel-item active">
                                                <img src="p1.jpg" class="d-block w-100" alt="...">
                                            </div>
                                            <div class="carousel-item">
                                                <img src="p2.jpg" class="d-block w-100" alt="...">
                                            </div>
                                            <div class="carousel-item">
                                                <img src="p3.jpg" class="d-block w-100" alt="...">
                                            </div>
                                        </div>
                                        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                                          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                            <span class="visually-hidden">Previous</span>
                                        </button>
                                        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                                               <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                              <span class="visually-hidden">Next</span>
                                         </button>
                                    </div>
                                    <div class="cate-list mb-3">
                                        <div class="row">

                                        </div>
                                    </div>

                                </div>
                            </div>
                        </div>
                    </section>
                    <div class="row">
                        <div class="container ">
                            <div class="d2 ">
                                <div class="product-list mb-0">
                                    <div class="product-titile border-bottom text-center">
                                        <strong class="text-warning fs-3">SẢN PHẨM MỚI</strong>
                                    </div>
                                    <div class="product-list-s pe-2 ps-2 mt-2">
                                        <div class="row ">
                                            <div class="col-md-3 text-center ">
                                                <a href="sp1.html"><img src="moi1.jpg " class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Nước sen Hậu Giang (toner) Cocoon giúp phục hồi ...</p>
                                                <p class="fs-6 fw-bold">178.000</p>
                                                <a href="sp1.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp2.html"><img src="moi2.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Tinh chất nghệ Hưng Yên C22 (serum) với ...</p>
                                                <p class="fs-5 fw-bold">417.000</p><br>
                                                <a href="sp2.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp3.html"><img src="moi3.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Sửa rữa mặt sen Hậu Giang</p>
                                                <p class="fs-5 fw-bold">138.000</p><br><br>
                                                <a href="sp3.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp4.html"><img src="moi4.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Nước sen Hậu Giang (toner) giúp phục hồi da đa năng ...</p>
                                                <p class="fs-5 fw-bold">264.000</p>
                                                <a href="sp4.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp5.html"><img src="moi5.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Sáp dưỡng ẩm đa năng sen Hậu Giang Cocoon</p>
                                                <p class="fs-5 fw-bold">178.000</p><br>
                                                <a href="sp5.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp6.html"><img src="moi6.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Sữa rửa mặt nghệ Hưng Yên Cocoon ...</p>
                                                <p class="fs-5 fw-bold">255.000</p><br>
                                                <a href="sp6.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp7.html"><img src="moi7.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Nước nghệ Hưng Yên(toner) Cocoon làm sang da ...</p>
                                                <p class="fs-5 fw-bold ">255.000</p>
                                                <a href="sp7.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp8.html"><img src="moi8.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Xịt khoáng nghệ Hưng Yên giúp sáng da ...</p>
                                                <p class="fs-5 fw-bold">196.000</p><br>
                                                <a href="sp8.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="product-list mb-0">
                                    <div class="product-titile border-bottom text-center">
                                        <strong class="text-warning fs-3">TẤT CẢ SẢM PHẨM TIÊU BIỂU</strong>
                                    </div>
                                    <div class="product-list-s  pe-2 ps-2 mt-2">
                                        <div class="row">
                                            <div class="col-md-3 text-center">
                                                <a href="sp9.html"><img src="đ1.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Túi Refill-Dầu gọi bưởi Cocoon giúp giảm gãy rụng và làm ...</p>
                                                <p class="fs-5 fw-bold">313.000</p>
                                                <a href="sp9.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp10.html"><img src="đ2.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Kem ủ tóc bưởi Cocoon giúp giảm rụng tóc và làm mền tóc</p>
                                                <p class="fs-5 fw-bold">187.000</p>
                                                <a href="sp10.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp11.html"><img src="đ3.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Kem ủ tóc bồ kết và vỏ bưởi Herbario-Vegan </p>
                                                <p class="fs-5 fw-bold">129.000</p><br>
                                                <a href="sp11.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp12.html"><img src="đ4.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Nước dưỡng tóc tinh dầu bưởi Cocoon giúp giảm gãy rụng và ...</p>
                                                <p class="fs-5 fw-bold">250.000</p>
                                                <a href="sp12.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp13.html"><img src="m8.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Nước nghệ Hưng Yên (toner) Cocoon làm sáng da và cấp ẩm</p>
                                                <p class="fs-5 fw-bold">178.000</p>
                                                <a href="sp13.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp14.html"><img src="d1.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Tẩy da chết đường thốt nốt An Giang Coc...</p>
                                                <p class="fs-5 fw-bold">158.000</p><br>
                                                <a href="sp14.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp15.html"><img src="d2.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Bơ dưỡng thể cafe Đak Lak Cocoon cho da mềm mịn và ...</p>
                                                <p class="fs-5 fw-bold">187.000</p>
                                                <a href="sp16.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp16.html"><img src="m1.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Nước tẩy trang rau má và diếp cá Herbario-Vegan...</p>
                                                <p class="fs-5 fw-bold">184.000</p><br>
                                                <a href="sp16.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp17.html"><img src="m2.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Tinh chất hoa hồng Cocoon Việt Nam ( rose serum )-Vegan...</p>
                                                <p class="fs-5 fw-bold">207.000</p>
                                                <a href="sp17.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp18.html"><img src="m3.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">sữa kem chống nắng bí đao-ráo mịn tự nhiên SPF 50+, ...</p>
                                                <p class="fs-5 fw-bold">119.000</p>
                                                <a href="sp18.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp19.html"><img src="m4.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Toner hoa đậu biết cân bằng da, cấp ẩm và chống lão hóa</p>
                                                <p class="fs-5 fw-bold">170.000</p>
                                                <a href="sp19.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp20.html"><img src="m5.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Boosted serum rau má và diếp cá Herbario-Vegan ...</p>
                                                <p class="fs-5 fw-bold">164.000</p><br>
                                                <a href="sp20.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp21.html"><img src="combo.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Combo Toner bí đao cân bằng da và Nước dưỡng tinh ...</p>
                                                <p class="fs-5 fw-bold">278.000</p>
                                                <a href="sp21.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp22.html"><img src="combo1.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Combo cafe tẩy da chết da mặt và tẩy da chết son môi Cocoon</p>
                                                <p class="fs-5 fw-bold">204.000</p>
                                                <a href="sp22.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp23.html"><img src="combo2.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold"> Combo Gell bí đao rửa mặt Cocoon và dung dịch chấm mụn...</p>
                                                <p class="fs-5 fw-bold">298.000</p>
                                                <a href="sp23.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>
                                            <div class="col-md-3 text-center">
                                                <a href="sp24.html"><img src="son.jpg" class="img-fluid"></a>
                                                <p class="fs-5 fw-bold">Combo son tẩy da chết môi Cà phê đắk lắk cocoon và...</p>
                                                <p class="fs-5 fw-bold">85.000</p><br>
                                                <a href="sp24.html" class="btn "><i class="bi bi-arrow-right-short">Xem chi tiết</i></a>
                                            </div>

                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="footer bg-dark text-white py-4">
        <div class="container a1">
            <div class="row">
                <h6>WEBSITE THUỘC QUYỀN CÔNG TY CỔ PHẦN Y&B</h6>
                <ul class="list-menu ">
                    <li class="li-menu"><a>GCNĐKKD: 0315803699 | SỞ KẾ HOẠCH VÀ ĐẦU TƯ TP. HỒ CHÍ MINH CẤP LẦN ĐẦU NGÀY 22/07/2019<br>
                        14D1, KHU PHỐ 1A, ĐƯỜNG QUỐC LỘ 1A, PHƯỜNG TÂN THỚI HIỆP, QUẬN 12, TP. HỒ CHÍ MINH, VIỆT NAM</a></li>
                    <a href="tel:19009300">ĐIỆN THOẠI:19009300</a> – EMAIL:
                    <a href="mailto:WE@COCOONVIETNAM.COM">WE@COCOONVIETNAM.COM</a>
                </ul>
            </div>
            <HR>
            <div class="row">
                <div class="row">
                    <h6>SẢN XUẤT VÀ CHỊU TRÁCH NHIỆM VỀ HÀNG HOÁ
                        <br> CÔNG TY TNHH NATURE STORY</h6>
                    <ul class="list-menu">
                        <li class="li-menu"><a>GCNĐKKD: 1101983767 / SỞ KẾ HOẠCH VÀ ĐẦU TƯ TỈNH LONG AN CẤP LẦN ĐẦU NGÀY: 15/04/2021<br>
                            LÔ LF24A-LF25 ĐƯỜNG SỐ 2, KHU CÔNG NGHIỆP XUYÊN Á, XÃ MỸ HẠNH BẮC, HUYỆN ĐỨC HÒA, TỈNH LONG AN, VIỆT NAM</a></li>
                        <a href="tel:19009300">ĐIỆN THOẠI:19009300</a> – EMAIL:
                        <a href="mailto:WE@COCOONVIETNAM.COM">WE@COCOONVIETNAM.COM</a>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    <script src="js/bootstrap.bundle.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

</body>
