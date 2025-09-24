<!doctype html>
<html lang="mr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>आपले कॉलेज</title>

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

  <style>
    body {scroll-behavior: smooth;}
    .hero {background: linear-gradient(180deg, rgba(13,110,253,0.08), rgba(13,110,253,0.02));padding: 60px 0;}
    .dept-card {min-height: 150px;}
    .notice-list li {margin-bottom: .6rem;}
    .gallery img {cursor:pointer;width:100%;height:180px;object-fit:cover;border-radius:8px;}
    footer {padding:24px 0;background:#f8f9fa;}
  </style>
</head>
<body>

  <!-- NAV -->
  <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">आपले कॉलेज</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="navMenu" class="collapse navbar-collapse">
        <ul class="navbar-nav ms-auto gap-2">
          <li class="nav-item"><a class="nav-link" href="#home">मुख्यपृष्ठ</a></li>
          <li class="nav-item"><a class="nav-link" href="#about">आमच्याविषयी</a></li>
          <li class="nav-item"><a class="nav-link" href="#departments">विभाग</a></li>
          <li class="nav-item"><a class="nav-link" href="#admissions">प्रवेश</a></li>
          <li class="nav-item"><a class="nav-link" href="#notices">सूचना</a></li>
          <li class="nav-item"><a class="nav-link" href="#gallery">गॅलरी</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">संपर्क</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- HERO -->
  <header id="home" class="hero">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-7">
          <h1 class="display-6">आपले स्वागत आहे <span class="text-primary">आपले कॉलेज</span></h1>
          <p class="lead">गुणवत्तापूर्ण शिक्षण • मजबूत मूल्ये • उज्वल भविष्य</p>
          <p><a href="#admissions" class="btn btn-primary">प्रवेशासाठी अर्ज करा</a> <a href="#notices" class="btn btn-outline-secondary">नवीन सूचना</a></p>
        </div>
        <div class="col-md-5 text-center">
          <img src="https://via.placeholder.com/380x220?text=College+Building" alt="college" class="img-fluid rounded shadow-sm">
        </div>
      </div>
    </div>
  </header>

  <!-- ABOUT -->
  <section id="about" class="py-5">
    <div class="container">
      <h2 class="mb-3">आमच्याविषयी</h2>
      <p>आमच्या कॉलेजचा इतिहास, ध्येय व दृष्टीकोन. गुणवत्तापूर्ण शिक्षणासोबत विद्यार्थ्यांच्या सर्वांगीण विकासासाठी प्रयत्नशील.</p>
      <div class="row">
        <div class="col-md-4">
          <h5>ध्येय</h5>
          <p>सर्वांसाठी शिक्षण आणि उज्ज्वल करिअरसाठी तयारी.</p>
        </div>
        <div class="col-md-4">
          <h5>सुविधा</h5>
          <p>ग्रंथालय, प्रयोगशाळा, क्रीडांगण, वसतिगृह, सभागृह.</p>
        </div>
        <div class="col-md-4">
          <h5>संपर्क कार्यालय</h5>
          <p>प्रवेश कार्यालय: +91-9699190113<br>ई-मेल: info@college.edu</p>
        </div>
      </div>
    </div>
  </section>

  <!-- DEPARTMENTS -->
  <section id="departments" class="py-5 bg-light">
    <div class="container">
      <h2 class="mb-4">विभाग</h2>
      <div class="row g-3">
        <div class="col-md-4">
          <div class="card dept-card p-3">
            <h5>संगणक विज्ञान</h5>
            <p>प्रोग्रामिंग, डेटा स्ट्रक्चर, नेटवर्क्स, कृत्रिम बुद्धिमत्ता.</p>
            <a class="btn btn-sm btn-outline-primary" href="#">अधिक माहिती</a>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card dept-card p-3">
            <h5>वाणिज्य</h5>
            <p>लेखाशास्त्र, व्यवसाय अभ्यास, अर्थशास्त्र.</p>
            <a class="btn btn-sm btn-outline-primary" href="#">अधिक माहिती</a>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card dept-card p-3">
            <h5>विज्ञान</h5>
            <p>भौतिकशास्त्र, रसायनशास्त्र, जीवशास्त्र प्रयोगशाळा.</p>
            <a class="btn btn-sm btn-outline-primary" href="#">अधिक माहिती</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ADMISSIONS -->
  <section id="admissions" class="py-5">
    <div class="container">
      <h2 class="mb-3">प्रवेश माहिती</h2>
      <p>प्रवेश घेण्यासाठी अर्ज फॉर्म डाउनलोड करा, आवश्यक कागदपत्रे जोडा आणि कॉलेजमध्ये सादर करा.</p>
      <ul>
        <li>पात्रता निकष</li>
        <li>आवश्यक कागदपत्रे</li>
        <li>महत्त्वाच्या तारखा</li>
      </ul>
      <a class="btn btn-success" href="#">अर्ज फॉर्म डाउनलोड करा (PDF)</a>
    </div>
  </section>

  <!-- NOTICES -->
  <section id="notices" class="py-5 bg-light">
    <div class="container">
      <h2 class="mb-3">सूचना</h2>
      <ul class="notice-list">
        <li><strong>१ सप्टेंबर २०२५:</strong> नवीन सत्र सुरू होणार.</li>
        <li><strong>२८ ऑगस्ट २०२५:</strong> प्रवेश परीक्षेचा निकाल जाहीर.</li>
        <li><strong>२० ऑगस्ट २०२५:</strong> क्रीडा दिन कार्यक्रम जाहीर.</li>
      </ul>
      <a class="btn btn-outline-secondary btn-sm" href="#">सर्व सूचना</a>
    </div>
  </section>

  <!-- GALLERY -->
  <section id="gallery" class="py-5">
    <div class="container">
      <h2 class="mb-4">गॅलरी</h2>
      <div class="row g-3">
        <div class="col-sm-6 col-md-4">
          <img src="https://via.placeholder.com/600x400?text=कार्यक्रम+1" alt="g1" data-bs-toggle="modal" data-bs-target="#imgModal" data-img="https://via.placeholder.com/1200x800?text=कार्यक्रम+1">
        </div>
        <div class="col-sm-6 col-md-4">
          <img src="https://via.placeholder.com/600x400?text=कार्यक्रम+2" alt="g2" data-bs-toggle="modal" data-bs-target="#imgModal" data-img="https://via.placeholder.com/1200x800?text=कार्यक्रम+2">
        </div>
        <div class="col-sm-6 col-md-4">
          <img src="https://via.placeholder.com/600x400?text=कार्यक्रम+3" alt="g3" data-bs-toggle="modal" data-bs-target="#imgModal" data-img="https://via.placeholder.com/1200x800?text=कार्यक्रम+3">
        </div>
      </div>
    </div>
  </section>

  <!-- IMAGE MODAL -->
  <div class="modal fade" id="imgModal" tabindex="-1">
    <div class="modal-dialog modal-xl modal-dialog-centered">
      <div class="modal-content">
        <div class="modal-body p-0">
          <img id="modalImage" src="" alt="large" style="width:100%; height:auto; display:block;">
        </div>
        <div class="modal-footer">
          <button class="btn btn-secondary" data-bs-dismiss="modal">बंद करा</button>
        </div>
      </div>
    </div>
  </div>

  <!-- CONTACT -->
  <section id="contact" class="py-5 bg-light">
    <div class="container">
      <h2 class="mb-3">संपर्क</h2>
      <div class="row">
        <div class="col-md-6">
          <form id="contactForm">
            <div class="mb-2">
              <input class="form-control" placeholder="नाव" required>
            </div>
            <div class="mb-2">
              <input class="form-control" placeholder="ई-मेल" type="email" required>
            </div>
            <div class="mb-2">
              <textarea class="form-control" placeholder="संदेश" rows="4" required></textarea>
            </div>
            <button class="btn btn-primary">पाठवा</button>
          </form>
        </div>
        <div class="col-md-6">
          <h5>पत्ता</h5>
          <p>goverment polytechnic collage, व्हीआयपी रोड,नांदेड<br>फोन: +91-9699190113</p>
          <div style="background:#e9ecef;height:200px;border-radius:8px;display:flex;align-items:center;justify-content:center">नकाशा Placeholder</div>
        </div>
      </div>
    </div>
  </section>
  <!-- FOOTER -->
  <footer class="text-center">
    <div class="container">
      <small>© <span id="year"></span> आपले कॉलेज. सर्व हक्क राखीव.</small>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

  <script>
    document.getElementById('year').innerText = new Date().getFullYear();
    const galleryImgs = document.querySelectorAll('#gallery img');
    const modalImg = document.getElementById('modalImage');
    galleryImgs.forEach(img => {
      img.addEventListener('click', (e) => {
        const large = e.currentTarget.getAttribute('data-img') || e.currentTarget.src;
        modalImg.src = large;
      });
    });
    document.getElementById('contactForm').addEventListener('submit', (e) => {
      e.preventDefault();
      alert('धन्यवाद! आपला संदेश प्राप्त झाला आहे (डेमो).');
      e.target.reset();
    });
  </script>

</body>
</html>
 
