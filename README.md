<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/13.4.0/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/13.4.0/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyAJSJ9xTsi1kfu56aZeaZx18hG0Fbrwca8",
    authDomain: "pen-packaging-job-centre.firebaseapp.com",
    projectId: "pen-packaging-job-centre",
    storageBucket: "pen-packaging-job-centre.firebasestorage.app",
    messagingSenderId: "47403438585",
    appId: "1:47403438585:web:4cc10c79d1a200c367ad28",
    measurementId: "G-RBLZMMLLVX"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
