<html>
<meta charset='UTF-8' />
<meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5'
  name='viewport' />
<meta content='IE=edge' http-equiv='X-UA-Compatible' />

<script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
<script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script>
<link href="https://htmlku.com/akuakan/play/style.css" rel="stylesheet" type="text/css" />

<head>
  <title>Maaf yee - suryaas</title>
  <link rel="icon" type="image/svg+xml" href="https://feeldreams.github.io/main-icon.png">
  <link rel="apple-touch-icon" href="https://feeldreams.github.io/main-icon.png">
</head>

<body>

  <div id="bodyblur">
    <!-- Wallpaper / Background --><img src="https://i.ibb.co/gPF2XhZ/b8fbc39ff32d93a15ce23fe9146e2387.webp"
      id="wallpaper" />
  </div>

  <div class="kumpulanstiker">
    <!-- Stiker untuk Konten -->
    <img src="https://feeldreams.github.io/pusn.gif" id="stiker1" />
    <img src="https://feeldreams.github.io/wortel.gif" id="stiker2" />
    <img src="https://feeldreams.github.io/mndkat.gif" id="stiker3" />
    <img src="https://feeldreams.github.io/ngumpet.gif" id="stiker4" />

    <div id='Content'>

      <div id="suratin" onClick="memulai();audio.play();">
        <!-- Surat --><img src="https://rayyscoding.github.io/envelope.png" />
      </div>
      <p id="ket">Klik Suratnya!</p>

      <div>
        <!-- Foto Akhir -->
        <img src="https://feeldreams.github.io/pandapukpuk.gif" id="fotoakhir" />
        <img src="https://feeldreams.github.io/gumush.gif" id="fotoakhir2" />
      </div>
      <div>
        <blockquote id='bq'>
          <p id="kalimat"></p>
          <p id="kalimatc"></p>
        </blockquote>
      </div>

      <!-- Tombol Kirim Pesan -->
      <div id="Tombol">
        <a onClick="sjawab()">
          <b>💌 Balas</b>
        </a>
      </div>

    </div>

    <script src="https://htmlku.com/akuakan/play/script.js"></script>

    <script type="text/javascript">
      async function pertama() {
        audio = new Audio('https://audio.jukehost.co.uk/5VfcVfr1D3fIU8m27X85m5HVkPyRIhQr'); showDiv();
      } pertama();


      async function pesan() {
        await swalst.fire({
          title: 'Hii Nofaaa! 😍',
          imageUrl: '' + stiker1.src,
        });

        await swalst.fire({
          title: 'Maaf ya Kalo Aku<br> Bikin Kamu Kesel 🫠',
          imageUrl: '' + stiker2.src,
        });

        await swalst.fire({
          title: 'Dan Bikin Kamu Marah 🫠',
          imageUrl: '' + stiker3.src,
        });

        await swalst.fire({
          title: 'Aku Cuma Mau Bilang.. ',
          imageUrl: '' + stiker4.src,
        });

        katangetik = "<b class='putih merah fontalt'>Maaf yaa</b> aku udah bikin kamu marah <br>aku salah paham soal kemarin,<br><br>aku kira kemarin kemarin kamu bohong ke aku gara gara aku udah ngebela belain pulang dari gresik ke surabaya, sebenarnya engga juga aku juga pen nonton sih tapi kalo kamu gamau ku bonceng juga gapapa ngomong aja terserah kamu <br><br>aku juga mau minta maaf kalo omonganku mungkin kasar yak, sebenarnya aku peduli sih hehe,cuman kita kan temenan doang <b>KATANYA</b> yaa jadi gapapa la kalo emang gamau ya ngomong aja gapapa <br><br>udah si itu aja yang mau ku omongin, Maaf yaa";
        katangetik2 = "<b>SEMANGAT TERUS CANTIKK</b> 💐🫣";

        setTimeout(kpemb, 200);
      }
    </script>
</body>

</html>
