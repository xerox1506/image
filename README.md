<header class="site-header">
  <h1>xelox Books & Past Papers</h1>
  <nav>
    <a href="#books">Vitabu</a>
    <head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>xelox Books & Past Papers</title>
  <meta name="description" content="Pata vitabu vya elimu na past papers za masomo mbalimbali. Wasiliana nasi kupitia WhatsApp." />
  <!-- Open Graph, Twitter Cards kama unataka kushare kwenye social media -->
</head>

    <a href="#papers">Past Papers</a>
    <a href="#contact">Wasiliana</a>
  </nav>
</header>

<main class="container">
  <section id="books">
    <h2>Vitabu vya Elimu</h2>
    <div class="item">
      <h3>EDUCATION IN DIPLOMA LEVEL </h3>

      <script>
  // dynamic year
  const footerP = document.querySelector(".site-footer p");
  if (footerP) {
    const year = new Date().getFullYear();
    footerP.innerHTML = `&copy; ${2025} xelox Books. All rights reserved.`;
  }

  // smooth scrolling behavior for nav links
  document.querySelectorAll('.site-header nav a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
      e.preventDefault();
      const target = document.querySelector(this.getAttribute('href'));
      if (target) {
        target.scrollIntoView({ behavior: 'smooth', block: 'start' });
      }
    });
  });

  // highlight nav link as user scrolls
  const sections = document.querySelectorAll('section[id]');
  window.addEventListener('scroll', () => {
    const scrollPos = window.scrollY + 100; // offset
    sections.forEach(sec => {
      const top = sec.offsetTop;
      const height = sec.offsetHeight;
      const id = sec.getAttribute('id');
      if (scrollPos >= top && scrollPos < top + height) {
        document.querySelectorAll('.site-header nav a').forEach(a => {
          a.classList.toggle('active', a.getAttribute('href') === `#${id}`);
        });
      }
    });
  });
</script>
      <a class="btn" href="https://drive.google.com/file/d/FILE_ID/view?usp=sharing" target="_blank">Pakua vitabu </a>


      <p> GOOD BOOKS OF DIPLOMA LEVEL .</p>
      <a class="btn" href="" target="_blank">downloard</a>
    </div>
    <div class="item">
      <h3>CURRICULUM NOTES AND PAST PAPERS</h3>
      <p>increase your perfomance easily.</p>
      
      <a class="btn" href="free downloard" target="_blank">downloard</a>
      
    </div>
  </section>

  <section id="papers">
    <h2> </h2>
    <div class="item">
      <h3>PSYCHOLOGY NOTES AND PASTPAPERS</h3>
      <p>psychology notes.</p>
      <a class="btn" href="free downloard" target="_blank">downloard</a>
    </div>
  </section>

  <section id="contact">
    <h2>Wasiliana Nasi</h2>
    <p>Tuma ujumbe kupitia WhatsApp: <a href="https://wa.me/255700000000" target="_blank">+255754770153</a></p>
  </section>
</main>

<footer class="site-footer">
  <p>&copy; 2025 lameck Books. All rights reserved.</p>
</footer>
<meta name="description" content="Vitabu na past papers kwa wanafunzi wa elimu. Pakua vitabu na ujifunze zaidi." />
<link rel="canonical" href="https://xerox-augustine.github.io/xelox-books-site/" />
<!-- HTML -->
<div class="subscribe-bar" id="subscribeBar">
  <span>Subscribe to our newsletter:</span>
  <input type="email" placeholder="Your email" id="subEmail" />
  <button id="subBtn">Subscribe</button>
  <span class="close-btn" id="closeBtn">&times;</span>
</div>
<div class="interaction-bar">
  <span class="like-btn">👍 <span class="like-count">0</span></span>
  <span class="dislike-btn">👎 <span class="dislike-count">0</span></span>
  <span class="comment-btn">💬 <span class="comment-count">0</span></span>
</div>
<input type="file" id="fileInput" accept="application/pdf" />
<div id="viewer"></div>
<div class="upload-book-section">
  <h3>Ongeza Kitabu kutoka kwenye Kompyuta yako</h3>
  <input type="file" id="bookFile" accept="application/pdf">
  <div id="bookViewer" class="book-viewer"></div>
</div>
<h3>Fungua Kitabu Mtandaoni</h3>
<a href="https://drive.google.com/file/d/FILE_ID/view" target="_blank">
  Bonyeza hapa kusoma kitabu (PDF)
</a>
<img src="your-image.jpg" alt="My Image" class="my-image">
<img src="https://i.postimg.cc/RZ4tY1GH/PXL-20250913-153128683-PORTRAIT.jpg" alt="Mimi" class="profile">
<div class="copy-box">
  <input type="text" id="copyInput" value="https://yourlink.com" readonly>
  <button onclick="copyToClipboard()">Copy Link</button>
</div>
<h2>Upload Past Paper</h2>
<form id="uploadForm">
  <input type="file" id="pastPaper" accept=".pdf,.docx" required>
  <button type="submit">Upload</button>
</form>
<p id="status"></p>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f5f5f5;
  color: #333;
}
body {
  background-color: black;
}

.site-header {
  background: #0066cc;
  color: #fff;
  padding: 1rem;
  text-align: center;
}
.site-header nav a {
  margin: 0 1rem;
  color: #fff;
  text-decoration: none;
}
.container {
  padding: 1rem;
}
.item {
  background: #fff;
  padding: 1rem;
  margin-bottom: 1rem;
  border-radius: 8px;
}
.btn {
  display: inline-block;
  padding: 0.5rem 1rem;
  background: #28a745;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
}
.btn:hover {
  background: #218838;
}
.site-footer {
  text-align: center;
  padding: 1rem;
  background: #eee;
}
/* juu ya kitu uliopo */
/* wrapper kwa grid layout kwa sections za vitabu / papers */
#books, #papers {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1rem;
}

/* navigation: kwa mobile weka hamburger menu (simple) */
.site-header nav {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.site-header nav a {
  padding: 0.5rem 1rem;
  margin: 0.25rem;
  border-radius: 4px;
  transition: background-color 0.3s;
}
.site-header nav a:hover {
  background-color: rgba(255,255,255,0.2);
}

/* ensure container width control */
.container {
  max-width: 1000px;
  margin: 0 auto;
  padding: 1rem;
}

/* footer ya kawaida */
.site-footer {
  background-color: #ddd;
  padding: 1rem;
}.site-header nav a.active {
  background-color: rgba(255,255,255,0.3);
}
/* CSS */
.subscribe-bar {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  background-color: #3498db; /* bluu, unaweza kubadilisha */
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 10px;
  z-index: 1000;
  box-shadow: 0 -2px 5px rgba(0,0,0,0.2);
}

.subscribe-bar input[type="email"] {
  padding: 5px;
  margin: 0 10px;
  border: none;
  border-radius: 3px;
}

.subscribe-bar button {
  padding: 6px 12px;
  border: none;
  background-color: #2c3e50;
  color: white;
  border-radius: 3px;
  cursor: pointer;
}

.subscribe-bar .close-btn {
  margin-left: 20px;
  font-size: 20px;
  cursor: pointer;
}.interaction-bar {
  position: fixed;
  top: 20px;      /* umbali kutoka juu */
  right: 20px;    /* umbali kutoka kulia */
  background-color: rgba(255, 255, 255, 0.9); /* picha nyuma inaonekana kidogo */
  padding: 8px 12px;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.2);
  display: flex;
  gap: 12px;
  font-size: 18px;
  align-items: center;
  z-index: 1000;
}

.interaction-bar span {
  cursor: pointer;
  display: flex;
  align-items: center;
}

.interaction-bar span span {
  margin-left: 4px;
  font-size: 16px;
}
.upload-book-section {
  margin-top: 40px;
  padding: 15px;
  border: 1px dashed #999;
  background-color: #f2f9ff;
  text-align: center;
}

.book-viewer iframe {
  width: 100%;
  height: 500px;
  margin-top: 15px;
  border: 1px solid #ccc;
}
.profile {
  width: 250px;   /* punguza size ya upana */
  height: auto;   /* inajipunguza kulingana na urefu */
  border-radius: 12px; /* hiari - kona za mviringo */
}
.copy-box {
  display: flex;
  align-items: center;
  gap: 8px;
  margin: 1rem 0; /* nafasi juu/chini */
  padding: 0.5rem;
  border: 1px solid #ccc;
  border-radius: 6px;
  background: #fff;
}
.copy-box input {
  flex: 1;
  padding: 6px;
  border: 1px solid #aaa;
  border-radius: 4px;
}
.copy-box button {
  padding: 6px 12px;
  background-color: #007bff;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
.copy-box button:hover {
  background-color: #0056b3;
}
document.getElementById('uploadForm').addEventListener('submit', function(e) {
  e.preventDefault();

  const file = 

// For future functionality like search, filtering etc.
// Currently not needed unless unaongeza features
// JavaScript (optional, kwa kufanya close ya bar)
document.getElementById("closeBtn").addEventListener("click", function() {
  document.getElementById("subscribeBar").style.display = "none";
});

document.getElementById("subBtn").addEventListener("click", function() {
  const email = document.getElementById("subEmail").value;
  if (email) {
    alert("Thank you for subscribing: " + email);
    // hapa unaweza ku-link na backend yako au API ya subscribe
    document.getElementById("subscribeBar").style.display = "none";
  } else {
    alert("Please enter a valid email.");
  }
});
// Get elements
const likeBtn = document.querySelector('.like-btn');
const dislikeBtn = document.querySelector('.dislike-btn');
const commentBtn = document.querySelector('.comment-btn');

const likeCountEl = document.querySelector('.like-count');
const dislikeCountEl = document.querySelector('.dislike-count');
const commentCountEl = document.querySelector('.comment-count');

// Initialize counters
let likes = 0, dislikes = 0, comments = 0;

likeBtn.addEventListener('click', () => {
  likes++;
  likeCountEl.textContent = likes;
});

dislikeBtn.addEventListener('click', () => {
  dislikes++;
  dislikeCountEl.textContent = dislikes;
});

commentBtn.addEventListener('click', () => {
  const comment = prompt("Enter your comment:");
  if (comment && comment.trim() !== "") {
    comments++;
    commentCountEl.textContent = comments;
    // optionally, you could also store/display the comment
  }
});
document.getElementById('fileInput').addEventListener('change', function(event) {
  const file = event.target.files[0];
  if (file) {
    const url = URL.createObjectURL(file);
    const iframe = document.createElement('iframe');
    iframe.src = url;
    iframe.width = "100%";
    iframe.height = "600px";
    document.getElementById('viewer').innerHTML = ""; 
    document.getElementById('viewer').appendChild(iframe);
  }
});
document.getElementById('bookFile').addEventListener('change', function(e) {
  const file = e.target.files[0];
  if (file && file.type === "application/pdf") {
    const fileURL = URL.createObjectURL(file);
    document.getElementById('bookViewer').innerHTML = `<iframe src="${fileURL}"></iframe>`;
  } else {
    alert("Tafadhali chagua faili la PDF pekee.");
  }
});
function copyToClipboard() {
  const input = document.getElementById("copyInput");
  input.select();
  input.setSelectionRange(0, 99999); // kwa support ya mobile
  navigator.clipboard.writeText(input.value)
    .then(() => {
      alert("Link copied: " + input.value);
    })
    .catch(err => {
      console.error("Failed to copy: ", err);
    });
}
document.getElementById('uploadForm').addEventListener('submit', function(e) {
  e.preventDefault();

  const file = document.getElementById('pastPaper').files[0];
  if(file) {
    // Hii haihifadhi file kwenye server kwa CodePen, lakini inaonyesha jina
    document.getElementById('status').innerText = `File "${file.name}" imechaguliwa.`;
  }
});
