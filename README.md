<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pengenalan HTML Tingkat Dasar</title>

    <meta name="author" content="Purnama Anaking">
    <meta name="keyword" content="Belajar HTML, Belajar Web">
    <meta name="description" content="Halaman praktikum modul 1 mata kuliah pemrograman web di program studi sistem informasi">
    <meta http-equiv="refresh" content="3">
    <meta name="robots" content="index, follow">

    <!-- Link: External CSS -->
    <link rel="stylesheet" href="assets/style.css">
    <!-- Link: Favicon -->
    <link rel="shortcut icon" href="assets/favicon.ico" type="image/x-icon">
    <!-- Internal Script -->
    <script>
    alert("Ini dari Inline Script");
    </script>
    <!-- External Script -->
    <script src="assets/script.js"></script>
    <!-- Style: Internal CSS -->
    <style media="all">
    .bg-secondary {
        background-color: gray;
    }
</style>
<style>
    table {
        border-spacing: 0;
        border-collapse: collapse;
        width: 100%;
    }

    th, td {
        border: solid 1px black;
        padding: 10px;
    }

    th {
        background-color: lightsteelblue;
    }

    tfoot {
        font-weight: bold;
    }

</style>
</head>

<body>
    <strong>Praktikum Pemrograman Web</strong>
    <hr>

    <h1>Pengenalan HTML Tingkat Dasar</h1> 
    <hr>

    <!-- Element Block Level -->
    <div>
        <h2>Element Block Level</h2>
        <hr>
        <div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore corporis temporibus, maxime labore blanditiis beatae sunt, totam eum quo laboriosam libero quibusdam qui quidem ab, neque magni expedita officia ipsa!</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis eius, aperiam consectetur ipsa aliquid soluta. Quo facilis enim veritatis odit facere! Placeat quidem ad veniam voluptas hic assumenda cupiditate molestiae.</p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Reiciendis quam ipsa repudiandae neque? Aperiam nihil, praesentium cupiditate consequatur quo pariatur dolores, veritatis ipsum soluta, ea sed voluptatem possimus deleniti tempore?</p>
        </div><div>Semangat!</div><p>Terus Belajar!</p>
    </div>
    <!-- Element Inline Level -->
    <div>
        <h2>Element Inline Level</h2>
        <hr>
        <div>
            <p>Lorem ipsum dolor, <strong>sit amet consectetur adipisicing elit</strong>. Porro corporis eveniet cum quod assumenda dolores architecto repudiandae, commodi aspernatur minima. Vel quis quibusdam iste, necessitatibus voluptatem explicabo repellendus magnam id.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. <em>Adipisci aspernatur nostrum laboriosam quas impedit commodi?</em> Sed praesentium assumenda, earum, repellendus adipisci maiores voluptas nulla possimus odit, saepe tempora esse neque! <span>Terus Belajar!</span></p>
        </div><div>Semangat!</div>
    </div>
    <!-- Elemen Text Formatting -->
    <div>
        <h2>Element Text Formatting</h2>
        <hr>
        <h1>Heading 1</h1>
        <h2>Heading 2</h2>
        <h3>Heading 3</h3>
        <h4>Heading 4</h4>
        <h5>Heading 5</h5> 
        <h6>Heading 6</h6>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aperiam fugit, reprehenderit optio perferendis dolore cupiditate corrupti non vel quam quisquam quo, perspiciatis assumenda eos ab voluptates rerum blanditiis tempore sunt.</p>
        <a href="https://is.ittelkom-sby.ac.id" target="_blank">Sistem Informasi IT Telkom Surabaya</a>
        <br><br>
        <div>
            <b>Bold Text</b>,
            <strong>Strong Text</strong>,
            <i>Italic Text </i>,
            <em>Emphasize Text</em>,
            <p><mark>Lorem ipsum</mark> dolor sit amet consectetur adipisicing elit. Magnam vitae laborum quis. Labore est impedit culpa assumenda nemo veritatis. Velit est odit voluptas aperiam, voluptatem nostrum corrupti tempore inventore! Quasi?</p>
            <small>Smaller Text</small>,
            <del>Deleted Text</del>,
            <ins>Inserted Text</ins>,
            <sub>Subscript Text</sub>,
            <sup>Superscript Text</sup>
        </div>
    </div>
     <!-- Element List -->
    <div>
        <h2>Element List</h2>
        <hr>
        <div>
            <h3>Ordered List</h3>
            <ol type="1">
                <li>Senin</li>
                <li>Selasa</li>
                <li>Rabu</li>
                <li>Kamis</li>
                <li>Jumat</li>
                <li>Sabtu</li>
                <li>Ahad</li>
            </ol>
        </div>
        <div>
            <h3>Unordered List</h3>
            <ul style="list-style-type:disc;">
                <li>Meja</li>
                <li>Kursi</li>
                <li>Papan Tulis</li>
                <li>TV</li>
                <li>Tas</li>
                <li>AC</li>
            </ul>
        </div>
        <div>
            <h3>Description List</h3>
            <dl>
                <dt>Title 1</dt>
                <dd>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis earum cumque natus autem molestiae ipsum illum minima qui ad, officiis vero! Autem consectetur quisquam aut fugiat placeat ea debitis voluptate?</dd>
                <dt>Title 2</dt>
                <dd>Lorem ipsum dolor sit amet consectetur adipisicing elit. At, iusto. Officiis aperiam earum sequi nihil sit natus asperiores quaerat! Molestias velit ea asperiores quia, sed laboriosam nisi consequuntur sint ex!</dd>
                <dt>Title 3</dt>
                <dd>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat ex nemo, beatae aliquam quos provident sequi nihil optio sint soluta perspiciatis error eos quisquam neque mollitia nobis quasi illum ratione.</dd>
            </dl>
        </div>
    </div>
    <!-- Element Image  -->
    <div>
        <h2>Element Image</h2>
        <hr>
        <!-- Relative Path -->
        <img src="assets/star.png" width="100" height="100" alt="Logo Bintang Kuning Biru" title="Logo Bintang 1"/>
        <!-- Absolute Path -->
        <img src="https://img.freepik.com/free-vector/start_53876-25533.jpg" width="100" height="100" alt="Logo Bintang Kuning" title="Logo Bintang 2"/>

        <div>
            <h3>Link dengan Image</h3>
            <a href="http://google.com" target="_blank">
            <img src="https://img.freepik.com/free-vector/start_53876-25533.jpg" width="100" height="100" alt="Logo Bintang Kuning" title="Logo Bintang 2"/>
            </a>
        </div>
    </div>
    <!-- Element Audio -->
    <div>
        <h2>Element Audio</h2>
        <hr>
        <audio controls>
            <source src="assets/horse.ogg" type="audio/ogg">
            <source src="assets/horse.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    </div>
    <!-- Element Video -->
    <div>
        <h2>Element Video</h2>
        <hr>
        <video width="320" height="240" controls>
            <source src="assets/movie.mp4" type="video/mp4">
            <source src="assets/movie.ogg" type="video/ogg">
            Your browser does not support the video tag.
        </video>
    </div>
    <table>
        <thead>
            <tr>
                <th width="10%">No</th>
                <th>Nama Barang</th>
                <th>Harga</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td style="text-align: center;">1.</td>
                <td>Meja</td>
                <td>Rp. 1.000.000</td>
            </tr>
            <tr>
                <td style="text-align: center;">2.</td>
                <td>Kursi</td>
                <td>Rp. 400.000</td>
            </tr>
            <tr>
                <td style="text-align: center;">3.</td>
                <td>Lemari</td>
                <td>Rp. 1.500.000</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="2" style="text-align: right;">Total</td>
                <td>Rp. 2.900.000</td>
            </tr>
        </tfoot>
    </table>
    <div>
        <h3>Nested Table</h3>
        <table>
            <tr>
                <th>
                    Nested Table
                </th>
            </tr>
            <tr>
                <td>
                    <table>
                        <thead>
                            <tr>
                                <th width="10%">No</th>
                                <th>Nama Barang</th>
                                <th>Harga</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td style="text-align: center;">1.</td>
                                <td>Meja</td>
                                <td>Rp. 1.000.000</td>
                            </tr>
                            <tr>
                                <td style="text-align: center;">2.</td>
                                <td>Kursi</td>
                                <td>Rp. 400.000</td>
                            </tr>
                            <tr>
                                <td style="text-align: center;">3.</td>
                                <td>Lemari</td>
                                <td>Rp. 1.500.000</td>
                            </tr>
                        </tbody>
                        <tfoot>
                            <tr>
                                <td colspan="2" style="text-align: right;">Total</td>
                                <td>Rp. 2.900.000</td>
                            </tr>
                        </tfoot>
                    </table>
                </td>
            </tr>
        </table>
    </div>

</body>
</html>
