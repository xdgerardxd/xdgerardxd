<div align="center">

<!-- HERO SECTION MEJORADA -->
<div style="
  background: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #f093fb 100%);
  padding: 4rem 2rem;
  border-radius: 25px;
  margin: 2rem 0;
  color: white;
  box-shadow: 0 25px 50px rgba(0,0,0,0.15);
  position: relative;
  overflow: hidden;
">
  <!-- Partículas animadas -->
  <div style="
    position: absolute;
    top: 0; left: 0; right: 0; bottom: 0;
    background: url('data:image/svg+xml,<svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 100 100\"><circle cx=\"20\" cy=\"20\" r=\"1\" fill=\"rgba(255,255,255,0.1)\"><animate attributeName=\"cy\" values=\"20;80;20\" dur=\"3s\" repeatCount=\"indefinite\"/></circle><circle cx=\"80\" cy=\"80\" r=\"1.5\" fill=\"rgba(255,255,255,0.1)\"><animate attributeName=\"cx\" values=\"80;20;80\" dur=\"4s\" repeatCount=\"indefinite\"/></circle></svg>');
    pointer-events: none;
  "></div>
  
  <div style="max-width: 1200px; margin: 0 auto;">
    <div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4rem;">
      
      <!-- IZQUIERDA: Nombre + Avatar FLOTANTE -->
      <div style="flex: 1; min-width: 300px; animation: float 6s ease-in-out infinite;">
        <h1 style="
          font-size: 4rem; 
          font-weight: 800; 
          margin: 0 0 1.5rem 0;
          background: linear-gradient(45deg, #fff, #f0f8ff, #e6e6fa);
          -webkit-background-clip: text;
          -webkit-text-fill-color: transparent;
          background-clip: text;
          text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        ">
          Gerardo David Morillo Rivas
        </h1>
        <img src="https://avatars.githubusercontent.com/u/TU-ID-AQUI?size=220" 
             alt="Gerardo David" 
             style="
               width: 220px; 
               height: 220px; 
               border-radius: 50%; 
               border: 6px solid rgba(255,255,255,0.4);
               box-shadow: 
                 0 20px 40px rgba(0,0,0,0.3),
                 0 0 30px rgba(255,255,255,0.2);
               transition: all 0.4s ease;
             "
             onmouseover="this.style.transform='scale(1.05) rotate(5deg)'; this.style.boxShadow='0 25px 50px rgba(0,0,0,0.4), 0 0 40px rgba(255,255,255,0.3)'"
             onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 20px 40px rgba(0,0,0,0.3), 0 0 30px rgba(255,255,255,0.2)'"
        >
      </div>
      
      <!-- DERECHA: Descripción + Botones -->
      <div style="flex: 1; min-width: 300px;">
        <h2 style="font-size: 2.2rem; margin-bottom: 2rem; opacity: 0.98;">
          🚀 <strong>Full Stack Developer</strong>
        </h2>
        <p style="font-size: 1.4rem; line-height: 1.8; opacity: 0.92; margin-bottom: 2rem;">
          Maestría en <strong>Frontend + Backend</strong><br>
          <span style="font-size: 1.2rem; color: #ffd700;">HTML5 • CSS • Tailwind • React • Node.js • Python • Docker</span>
        </p>
        
        <!-- BOTONES ANIMADOS -->
        <div style="display: flex; gap: 1rem; flex-wrap: wrap;">
          <a href="mailto:tu-email@gmail.com" style="
            background: rgba(255,255,255,0.2);
            color: white;
            padding: 1rem 2rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            backdrop-filter: blur(10px);
            border: 2px solid rgba(255,255,255,0.3);
            transition: all 0.3s ease;
            font-size: 1.1rem;
          "
          onmouseover="this.style.background='rgba(255,255,255,0.3)'; this.style.transform='translateY(-3px)'"
          onmouseout="this.style.background='rgba(255,255,255,0.2)'; this.style.transform='translateY(0)'"
          >📧 Contáctame</a>
          
          <a href="https://linkedin.com/in/gerardo-morillo" style="
            background: rgba(0,123,255,0.2);
            color: white;
            padding: 1rem 2rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            backdrop-filter: blur(10px);
            border: 2px solid rgba(0,123,255,0.4);
            transition: all 0.3s ease;
            font-size: 1.1rem;
          "
          onmouseover="this.style.background='rgba(0,123,255,0.4)'; this.style.transform='translateY(-3px)'"
          onmouseout="this.style.background='rgba(0,123,255,0.2)'; this.style.transform='translateY(0)'"
          >💼 LinkedIn</a>
        </div>
      </div>
    </div>
  </div>
</div>

<style>
@keyframes float {
  0%, 100% { transform: translateY(0px); }
  50% { transform: translateY(-10px); }
}
</style>

<!-- SKILLS CARDS INTERACTIVAS -->
<h2 style="margin: 4rem 0 2rem 0; font-size: 2.8rem; color: #2c3e50; text-align: center;">
  🛠️ <strong>Habilidades Técnicas</strong>
</h2>

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(380px, 1fr)); gap: 2.5rem; max-width: 1200px; margin: 0 auto;">
  
  <!-- CARD 1: Frontend -->
  <div style="
    background: linear-gradient(145deg, #ffffff, #f0f2f5);
    border-radius: 25px;
    padding: 2.5rem;
    box-shadow: 0 20px 40px rgba(0,0,0,0.1);
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    border-top: 6px solid #e74c3c;
    position: relative;
    overflow: hidden;
  "
  onmouseover="this.style.transform='translateY(-15px) scale(1.02)'; this.style.boxShadow='0 30px 60px rgba(231,76,60,0.3)'"
  onmouseout="this.style.transform='translateY(0) scale(1)'; this.style.boxShadow='0 20px 40px rgba(0,0,0,0.1)'"
  >
    <div style="position: absolute; top: -50px; right: -50px; font-size: 6rem; opacity: 0.1;">⚡</div>
    <div style="font-size: 3.5rem; margin-bottom: 1.5rem; display: flex; gap: 1rem;">
      <span style="color: #e74c3c;">⚡</span> 
      <span style="color: #3498db;">🎨</span>
    </div>
    <h3 style="color: #2c3e50; margin-bottom: 1rem; font-size: 1.8rem;">Frontend Mastery</h3>
    <p style="color: #7f8c8d; line-height: 1.7; font-size: 1.1rem;">
      <strong>React • Vue • Tailwind CSS</strong><br>
      <strong>HTML5 • CSS3 • Bootstrap 5</strong><br>
      Animaciones • PWA • Performance 95+
    </p>
  </div>
  
  <!-- CARD 2: Backend -->
  <div style="
    background: linear-gradient(145deg, #ffffff, #f0f2f5);
    border-radius: 25px;
    padding: 2.5rem;
    box-shadow: 0 20px 40px rgba(0,0,0,0.1);
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    border-top: 6px solid #27ae60;
    position: relative;
    overflow: hidden;
  "
  onmouseover="this.style.transform='translateY(-15px) scale(1.02)'; this.style.boxShadow='0 30px 60px rgba(39,174,96,0.3)'"
  onmouseout="this.style.transform='translateY(0) scale(1)'; this.style.boxShadow='0 20px 40px rgba(0,0,0,0.1)'"
  >
    <div style="position: absolute; top: -50px; right: -50px; font-size: 6rem; opacity: 0.1;">🔥</div>
    <div style="font-size: 3.5rem; margin-bottom: 1.5rem; display: flex; gap: 1rem;">
      <span style="color: #27ae60;">🐍</span> 
      <span style="color: #9b59b6;">⚙️</span>
    </div>
    <h3 style="color: #2c3e50; margin-bottom: 1rem; font-size: 1.8rem;">Backend & DevOps</h3>
    <p style="color: #7f8c8d; line-height: 1.7; font-size: 1.1rem;">
      <strong>Node.js • Express • Python</strong><br>
      <strong>MongoDB • PostgreSQL • Docker</strong><br>
      APIs REST/GraphQL • Microservicios
    </p>
  </div>
  
  <!-- CARD 3: Mobile -->
  <div style="
    background: linear-gradient(145deg, #ffffff, #f0f2f5);
    border-radius: 25px;
    padding: 2.5rem;
    box-shadow: 0 20px 40px rgba(0,0,0,0.1);
    transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    border-top: 6px solid #f39c12;
    position: relative;
    overflow: hidden;
  "
  onmouseover="this.style.transform='translateY(-15px) scale(1.02)'; this.style.boxShadow='0 30px 60px rgba(243,156,18,0.3)'"
  onmouseout="this.style.transform='translateY(0) scale(1)'; this.style.boxShadow='0 20px 40px rgba(0,0,0,0.1)'"
  >
    <div style="position: absolute; top: -50px; right: -50px; font-size: 6rem; opacity: 0.1;">📱</div>
    <div style="font-size: 3.5rem; margin-bottom: 1.5rem; display: flex; gap: 1rem;">
      <span style="color: #f39c12;">📱</span> 
      <span style="color: #34495e;">💻</span>
    </div>
    <h3 style="color: #2c3e50; margin-bottom: 1rem; font-size: 1.8rem;">Mobile First</h3>
    <p style="color: #7f8c8d; line-height: 1.7; font-size: 1.1rem;">
      <strong>Responsive • PWA • SPA</strong><br>
      <strong>React Native • Flutter</strong><br>
      100% Mobile Optimized • Lighthouse 100
    </p>
  </div>
</div>

<!-- STATS MEJORADAS -->
<div style="margin: 4rem 0;">
  <h2 style="text-align: center; margin-bottom: 2.5rem; font-size: 2.5rem; color: #2c3e50; background: linear-gradient(45deg, #667eea, #764ba2); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">
    📈 GitHub Analytics
  </h2>
  
  <div style="display: flex; justify-content: center; gap: 2rem; flex-wrap: wrap; max-width: 1000px; margin: 0 auto;">
    <img src="https://github-readme-stats.vercel.app/api?username=TU-USUARIO&show_icons=true&theme=dark&hide_border=true&bg_color=0f111a&title_color=fed3ab&text_color=f0f6fc&hide=stars,prs&card_width=400" 
         style="border-radius: 20px; box-shadow: 0 20px 40px rgba(0,0,0,0.2); transition: transform 0.3s ease;"
         onmouseover="this.style.transform='scale(1.05)'"
         onmouseout="this.style.transform='scale(1)'"/>
    <img src="https://github-readme-streak-stats.herokuapp.com?user=TU-USUARIO&theme=dark&hide_border=true&background=0f111a&stroke=ffd3ab&ring=fed3ab&fire=ff6b6b&currStreakLabel=f0f6fc"
         style="border-radius: 20px; box-shadow: 0 20px 40px rgba(0,0,0,0.2); transition: transform 0.3s ease;"
         onmouseover="this.style.transform='scale(1.05)'"
         onmouseout="this.style.transform='scale(1)'"/>
  </div>
</div>

<!-- PROYECTOS DESTACADOS MEJORADOS -->
<h2 style="margin: 4rem 0 2rem 0; font-size: 2.8rem; color: #2c3e50; text-align: center;">
  🔥 <strong>Proyectos Premium</strong>
</h2>

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 2.5rem; max-width: 1200px; margin: 0 auto;">
  
  <a href="https://github.com/TU-USUARIO/proyecto1" style="
    text-decoration: none;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 2.5rem;
    border-radius: 25px;
    text-align: center;
    transition: all 0.4s ease;
    box-shadow: 0 15px 35px rgba(102,126,234,0.4);
    position: relative;
    overflow: hidden;
  "
  onmouseover="this.style.transform='translateY(-10px)'; this.style.boxShadow='0 25px 50px rgba(102,126,234,0.6)'"
  onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 15px 35px rgba(102,126,234,0.4)'"
  >
    <div style="font-size: 4rem; margin-bottom: 1rem;">🌐</div>
    <h3 style="margin: 0 0 1rem 0; font-size: 1.8rem;">Portfolio PRO</h3>
    <p style="margin: 0; opacity: 0.95; font-size: 1.1rem;">React + Tailwind + Framer Motion</p>
    <div style="margin-top: 1.5rem; font-size: 1.2rem; color: #ffd700;">⭐ 120 Stars</div>
  </a>
  
  <a href="https://github.com/TU-USUARIO/proyecto2" style="
    text-decoration: none;
    background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    color: white;
    padding: 2.5rem;
    border-radius: 25px;
    text-align: center;
    transition: all 0.4s ease;
    box-shadow: 0 15px 35px rgba(240,147,251,0.4);
    position: relative;
    overflow: hidden;
  "
  onmouseover="this.style.transform='translateY(-10px)'; this.style.boxShadow='0 25px 50px rgba(240,147,251,0.6)'"
  onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 15px 35px rgba(240,147,251,0.4)'"
  >
    <div style="font-size: 4rem; margin-bottom: 1rem;">⚙️</div>
    <h3 style="margin: 0 0 1rem 0; font-size: 1.8rem;">E-Commerce API</h3>
    <p style="margin: 0; opacity: 0.95; font-size: 1.1rem;">Node.js + Express + MongoDB</p>
    <div style="margin-top: 1.5rem; font-size: 1.2rem; color: #ffd700;">⭐ 85 Stars</div>
  </a>
  
  <a href="https://github.com/TU-USUARIO/proyecto3" style="
    text-decoration: none;
    background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
    color: white;
    padding: 2.5rem;
    border-radius: 25px;
    text-align: center;
    transition: all 0.4s ease;
    box-shadow: 0 15px 35px rgba(79,172,254,0.4);
    position: relative;
    overflow: hidden;
  "
  onmouseover="this.style.transform='translateY(-10px)'; this.style.boxShadow='0 25px 50px rgba(79,172,254,0.6)'"
  onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 15px 35px rgba(79,172,254,0.4)'"
  >
    <div style="font-size: 4rem; margin-bottom: 1rem;">📱</div>
    <h3 style="margin: 0 0 1rem 0; font-size: 1.8rem;">Task Manager App</h3>
    <p style="margin: 0; opacity: 0.95; font-size: 1.1rem;">React Native + Firebase + Redux</p>
    <div style="margin-top: 1.5rem; font-size: 1.2rem; color: #ffd700;">⭐ 65 Stars</div>
  </a>
</div>

<!-- CONTACTO ULTRA MODERNO -->
<div style="
  background: linear-gradient(135deg, #2c3e50 0%, #34495e 50%, #1a252f 100%);
  padding: 4rem 2rem;
  border-radius: 25px;
  margin: 4rem 0;
  color: white;
  text-align: center;
  position: relative;
  overflow: hidden;
">
  <div style="position: absolute; top: 0; left: 0; right: 0; height: 5px; background: linear-gradient(90deg, #667eea, #764ba2, #f093fb, #667eea); background-size: 300% 100%; animation: gradient 3s ease infinite;"></div>
  
  <h2 style="margin-bottom: 2rem; font-size: 2.5rem; position: relative;">
    💬 <strong>Conéctate conmigo</strong>
  </h2>
  
  <div style="display: flex; justify-content: center; gap: 2rem; flex-wrap: wrap; max-width: 800px; margin: 0 auto;">
    <a href="mailto:tu-email@gmail.com" style="
      color: white; 
      font-size: 1.6rem;
      padding: 1.5rem 2.5rem;
      border-radius: 50px;
      text-decoration: none;
      background: rgba(255,255,255,0.1);
      backdrop-filter: blur(15px);
      border: 2px solid rgba(255,255,255,0.2);
      transition: all 0.3s ease;
      display: flex; align-items: center; gap: 1rem;
    "
    onmouseover="this.style.background='rgba(255,255,255,0.2)'; this.style.transform='translateY(-5px)'"
    onmouseout="this.style.background='rgba(255,255,255,0.1)'; this.style.transform='translateY(0)'"
    >📧 Email</a>
    
    <a href="https://linkedin.com/in/gerardo-morillo" style="
      color: white; 
      font-size: 1.6rem;
      padding: 1.5rem 2.5rem;
      border-radius: 50px;
      text-decoration: none;
      background: rgba(0,123,255,0.2);
      backdrop-filter: blur(15px);
      border: 2px solid rgba(0,123,255,0.3);
      transition: all 0.3s ease;
      display: flex; align-items: center; gap: 1rem;
    "
    onmouseover="this.style.background='rgba(0,123,255,0.4)'; this.style.transform='translateY(-5px)'"
    onmouseout="this.style.background='rgba(0,123,255,0.2)'; this.style.transform='translateY(0)'"
    >💼 LinkedIn</a>
    
    <a href="https://wa.me/TU-NUMERO" style="
      color: white; 
      font-size: 1.6rem;
      padding: 1.5rem 2.5rem;
      border-radius: 50px;
      text-decoration: none;
      background: rgba(40,213,40,0.2);
      backdrop-filter: blur(15px);
      border: 2px solid rgba(40,213,40,0.4);
      transition: all 0.3s ease;
      display: flex; align-items: center; gap: 1rem;
    "
    onmouseover="this.style.background='rgba(40,213,40,0.4)'; this.style.transform='translateY(-5px)'"
    onmouseout="this.style.background='rgba(40,213,40,0.2)'; this.style.transform='translateY(0)'"
    >📱 WhatsApp</a>
  </div>
</div>

<style>
@keyframes float {
  0%, 100% { transform: translateY(0px); }
  50% { transform: translateY(-10px); }
}

@keyframes gradient {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
</style>

<!-- FOOTER EPIC -->
<div align="center" style="margin-top: 4rem; padding: 2.5rem; background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%); border-radius: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.1);">
  <p style="color: #6c757d; font-size: 1rem; margin: 0;">
    <strong>✨ Hecho con ❤️ y ☕ usando GitHub</strong> &nbsp;•&nbsp; 
    <a href="https://github.com/TU-USUARIO/tu-readme/commits/main" style="color: #007bff; font-weight: 600; text-decoration: none;">Última actualización</a>
  </p>
  <p style="color: #adb5bd; font-size: 0.9rem; margin-top: 0.5rem;">
    <strong>🚀 Disponible para proyectos freelance</strong>
  </p>
</div>

</div>
