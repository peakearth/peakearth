<!DOCTYPE html>
<html lang = "en">
<head>
  <meta charset = "UTF-8">
  <meta name = "viewport" content="width=device-width, initial-scale=1.0">
  <title>2-Column Layout</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    .container {
      display: flex;
      flex-wrap: wrap; /* 모바일 대응을 위해 감싸는 구조 */
    }
    .column {
      flex: 1 1 50%; /* 각 열이 50% 차지 */
      padding: 20px;
      box-sizing: border-box;
    }
    .column h3, .column h4 {
      text-align: center;
    }
    /* 좌우 여백, 모바일 크기에 맞춘 조정 */
    @media (max-width: 768px) {
      .column {
        flex: 1 1 100%; /* 화면이 작아지면 한 줄로 전환 */
      }
    }
  </style>
</head>
<body>

<!-- 전체 컨테이너 -->
<div class = "container">

  <!-- 왼쪽 단 -->
  <div class = "column" style = "background-color: #f9f9f9;">

    <!-- 자기소개 -->
    <h3 align = "center">𝑯𝒊! 𝑾𝒆𝒍𝒄𝒐𝒎𝒆 :)</h3>
    <h4 align = "center">𝚄𝚛𝚋𝚊𝚗 𝙿𝚕𝚊𝚗𝚗𝚎𝚛 / 𝙶𝙸𝚂 𝙳𝚎𝚟𝚎𝚕𝚘𝚙𝚎𝚛 / 𝙳𝚊𝚝𝚊 𝙴𝚗𝚐𝚒𝚗𝚎𝚎𝚛</h4>
    <div align = "center">
      𝐼 𝑓𝑜𝑐𝑢𝑠 𝑜𝑛 𝑠𝑜𝑙𝑣𝑖𝑛𝑔 𝑈𝑅𝐵𝐴𝑁 𝐼𝑆𝑆𝑈𝐸𝑆 𝑢𝑠𝑖𝑛𝑔 𝐺𝐼𝑆 & 𝐷𝑎𝑡𝑎 𝐸𝑛𝑔𝑖𝑛𝑒𝑒𝑟𝑖𝑛𝑔.<br>
      𝐼`𝑚 𝐼𝑛𝑡𝑒𝑟𝑠𝑡𝑒𝑑 𝐴𝑡 𝐺𝐼𝑆, 𝐷𝑎𝑡𝑎 𝐴𝑛𝑎𝑙𝑦𝑠𝑖𝑠 𝐴𝑛𝑑 𝑉𝑖𝑠𝑢𝑎𝑙𝑖𝑧𝑎𝑡𝑖𝑜𝑛.<br>
    </div>

    <h3 align = "center"></h3>
    <h4 align = "center"> 도시공학 / GIS / 데이터 엔지니어링</h4>
    <div align = "center">
      제 Github에 방문해 주셔서 감사합니다 <br>
      <br>
      저는 GIS, 데이터 분석과 시각화를 통해 도시 문제의 해결에 주력하고 있습니다. <br>
      도시공학과 빅데이터의 융합을 통해, 시민들이 보다 안전하고 편리하게 생활할 수 있는 도시계획을 연구하고자 합니다. <br>
    </div>

    <!-- Contact -->
    <h3 align="center">📫 𝑪𝒐𝒏𝒕𝒂𝒄𝒕</h3>
    <div align="center">
      <a href="mailto:1933874@donga.ac.kr">
        <img src="https://img.shields.io/badge/Send%20E--Mail!-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
      </a>
    </div>

    <!-- About Me -->
    <h3 align="center">🐱 𝑨𝒃𝒐𝒖𝒕 𝑴𝒆!</h3>
    <div align="center">
      <a href="https://bit.ly/4fMvYdr">
        <img src="https://img.shields.io/badge/About%20Me!-F3F3F3.svg?style=for-the-badge&logo=notion&logoColor=black"/>
      </a>
    </div>
  </div>

  <!-- 오른쪽 단 -->
  <div class="column" style="background-color: #ffffff;">

    <!-- Tech Stack -->
    <h3 align="center">✨ 𝑻𝒆𝒄𝒉 𝑺𝒕𝒂𝒄𝒌</h3>
    <div align="center">
      <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
      <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=R&logoColor=white" />
    </div>
    <div align="center">
      <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=MariaDB&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white" />
    </div>

    <!-- 공부 중인 것들 -->
    <h3 align = "center">📚 𝑺𝒕𝒖𝒅𝒚𝒊𝒏𝒈 </h3>
    <div align = "center">
      <img src = "https://img.shields.io/badge/Java-E11F21.svg?style=for-the-badge&logo=java&logoColor=white" />
    </div>
  
    <div align = "center">
      <img src = "https://img.shields.io/badge/Hadoop-66CCFF.svg?style=for-the-badge&logo=Apache%20hadoop&logoColor=black" />
      <img src = "https://img.shields.io/badge/scikitlearn-F7931E.svg?style=for-the-badge&logo=scikitlearn&logoColor=white" />
    </div>

    <!-- Tools for Cording -->
    <h3 align = "center">🛠 𝑻𝒐𝒐𝒍𝒔 𝒇𝒐𝒓 𝒄𝒐𝒓𝒅𝒊𝒏𝒈 </h3>
    <div align = "center">
      <img src = "https://img.shields.io/badge/git-F05033.svg?style=for-the-badge&logo=git&logoColor=white" />
      <img src = "https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logo=github&logoColor=white" />
      <img src = "https://img.shields.io/badge/Anaconda-44A833.svg?style=for-the-badge&logo=Anaconda&logoColor=white" />
    </div>
    
    <div align = "center">
      <img src = "https://img.shields.io/badge/VS%20Code-22ABF3.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white" />&nbsp
      <img src = "https://img.shields.io/badge/Rstudio%20IDE-75AADB.svg?style=for-the-badge&logo=rstudio-ide&logoColor=white" />
      <img src = "https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white" />
    </div>
    
    <!-- Tools for Urban Planning -->
    <h3 align="center">🛠 𝑻𝒐𝒐𝒍𝒔 𝒇𝒐𝒓 𝑼𝒓𝒃𝒂𝒏 𝑷𝒍𝒂𝒏𝒏𝒊𝒏𝒈</h3>
    <div align = "center">
      <img src = "https://img.shields.io/badge/QGIS-589632.svg?style=for-the-badge&logo=qgis&logoColor=white" />
      <img src = "https://img.shields.io/badge/ArcGIS-2C7AC3.svg?style=for-the-badge&logo=ArcGIS&logoColor=white" />
    </div>
    
    <div align = "center">
      <img src = "https://img.shields.io/badge/Autocad-E51050.svg?style=for-the-badge&logo=Autocad&logoColor=white" />
      <img src = "https://img.shields.io/badge/SketchUp-005F9E.svg?style=for-the-badge&logo=Sketchup&logoColor=white" />
      <img src = "https://img.shields.io/badge/V--Ray-91b6e2.svg?style=for-the-badge&logo=Vray&logoColor=white" />
    </div>
    
    <div align = "center">
        <img src = "https://img.shields.io/badge/Adobe%20illustrator-FF9A00.svg?style=for-the-badge&logo=adobeillustrator&logoColor=white" />
        <img src = "https://img.shields.io/badge/Adobe%20Photoshop-31A8FF.svg?style=for-the-badge&logo=adobephotoshop&logoColor=white" />

    <!-- Github Stats -->
    <h3 align="center">📈 𝑷𝒓𝒐𝒋𝒆𝒄𝒕 𝑺𝒕𝒂𝒕𝒔</h3>
    <div align="center">
      <img src="https://github-readme-stats.vercel.app/api?username=peakearth&show_icons=true&theme=transparent&card_width=220" />
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=peakearth&theme=transparent" />
      <br>
      <p align="center">
        <a href="https://solved.ac/liilliiilliliiil/">
          <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=liilliiilliliiil" />
        </a>
      </p>
    </div>
  </div>
</div>

</body>
</html>
