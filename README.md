<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CUSTOMTECH | Equipos custom-made para I+D e Innovación</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Montserrat -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700;800;900&display=swap">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #ffffff;
            color: #000000;
        }
    </style>
</head>
<body class="bg-white text-black antialiased selection:bg-black selection:text-white">

    <!-- BARRA DE NAVEGACIÓN COMPACTA -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-white/95 backdrop-blur-md border-b border-black/10">
        <div class="max-w-6xl mx-auto px-4 h-16 flex items-center justify-between">
            <!-- LOGOTIPO VECTORIAL INTEGRADO -->
            <a href="#inicio" class="flex items-center gap-2">
                <svg class="h-8 w-auto" viewBox="0 0 160 45" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <text x="0" y="20" font-family="Montserrat" font-weight="900" font-size="18" fill="black" letter-spacing="-0.5">CUSTOM</text>
                    <text x="40" y="38" font-family="Montserrat" font-weight="900" font-size="18" fill="black" letter-spacing="-0.5">TECH</text>
                    <g transform="translate(120, 5)">
                        <rect width="32" height="32" fill="black"/>
                        <rect x="0" y="4" width="28" height="2.5" fill="#ccff00"/>
                        <rect x="0" y="11" width="32" height="2.5" fill="#ccff00"/>
                        <rect x="0" y="18" width="28" height="2.5" fill="#ccff00"/>
                        <rect x="0" y="25" width="32" height="2.5" fill="#ccff00"/>
                    </g>
                </svg>
            </a>
            
            <nav class="hidden md:flex items-center gap-6 font-medium text-xs uppercase tracking-wider text-black/70">
                <a href="#inicio" class="hover:text-black transition-colors">Inicio</a>
                <a href="#capacidades" class="hover:text-black transition-colors">Capacidades</a>
                <a href="#galeria" class="hover:text-black transition-colors">Galería I+D</a>
                <a href="#contacto" class="hover:text-black transition-colors">Contacto</a>
            </nav>

            <a href="https://wa.me/56984029443" target="_blank" class="bg-black text-white px-4 py-2 rounded-lg font-bold text-xs tracking-wide uppercase hover:bg-neutral-800 transition-all flex items-center gap-2">
                <i class="fab fa-whatsapp text-sm text-emerald-400"> +56 9 8402 9443</i>
            </a>
        </div>
    </header>

    <!-- INICIO / HERO BREVE -->
    <section id="inicio" class="pt-28 pb-12 px-4 max-w-6xl mx-auto text-center">
        <div class="max-w-2xl mx-auto space-y-4">
            <span class="text-xs font-bold uppercase tracking-widest bg-black text-white px-3 py-1 rounded-full">I+D e Innovación</span>
            <h1 class="text-3xl sm:text-5xl font-black tracking-tight leading-tight">
                Equipos custom-made para investigación y tecnología
            </h1>
            <p class="text-sm sm:text-base text-neutral-600">
                Diseño y fabricación a medida de sistemas, columnas y prototipos de alta precisión para la industria y la ciencia.
            </p>
        </div>
    </section>

    <!-- CAPACIDADES RÁPIDAS -->
    <section id="capacidades" class="py-12 px-4 max-w-6xl mx-auto border-t border-black/10">
        <h2 class="text-xl font-bold uppercase tracking-wider text-center mb-8">Nuestras Capacidades</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 text-center">
            <div class="p-6 border border-black/10 rounded-xl bg-neutral-50">
                <i class="fas fa-cogs text-2xl mb-3"></i>
                <h3 class="font-bold text-sm mb-1">Mecánica CNC</h3>
                <p class="text-xs text-neutral-600">Torneado, fresado y soldadura plástica y metálica de precisión.</p>
            </div>
            <div class="p-6 border border-black/10 rounded-xl bg-neutral-50">
                <i class="fas fa-shield-alt text-2xl mb-3"></i>
                <h3 class="font-bold text-sm mb-1">Polímeros & Acrílicos</h3>
                <p class="text-xs text-neutral-600">Policarbonato y acrílicos de alta transparencia técnica.</p>
            </div>
            <div class="p-6 border border-black/10 rounded-xl bg-neutral-50">
                <i class="fas fa-cubes text-2xl mb-3"></i>
                <h3 class="font-bold text-sm mb-1">Metales & Inoxidables</h3>
                <p class="text-xs text-neutral-600">Acero AISI 316L, aluminio, bronce y cobre para laboratorio.</p>
            </div>
        </div>
    </section>

    <!-- GALERÍA (FOTOS LOCALES CON MINIATURAS Y ZOOM) -->
    <section id="galeria" class="py-12 px-4 max-w-6xl mx-auto border-t border-black/10">
        <h2 class="text-xl font-bold uppercase tracking-wider text-center mb-2">Galería de Proyectos</h2>
        <p class="text-xs text-neutral-500 text-center mb-8">Toca cualquier miniatura para ampliarla</p>
        
        <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-3">
            <!-- Item 1 -->
            <div class="border border-black/10 rounded-lg overflow-hidden cursor-pointer group bg-neutral-100" onclick="openModal('Imagen002.png', 'Planta de Flotación en Columna', 'Estructura modular de acero con columnas de acrílico técnico de alta transparencia y manifold de distribución.')">
                <div class="h-32 overflow-hidden relative bg-neutral-200">
                    <img src="Imagen002.png" alt="Planta de Flotación" class="w-full h-full object-cover group-hover:scale-105 transition-transform" onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1581092335397-9583fe92d232?auto=format&fit=crop&w=400&q=80'">
                </div>
                <div class="p-2 text-center text-xs font-bold truncate">Planta de Flotación</div>
            </div>

            <!-- Item 2 -->
            <div class="border border-black/10 rounded-lg overflow-hidden cursor-pointer group bg-neutral-100" onclick="openModal('Imagen003.png', 'Molino SAG para Minería', 'Desarrollado para pruebas experimentales de conminución y molienda a escala de laboratorio.')">
                <div class="h-32 overflow-hidden relative bg-neutral-200">
                    <img src="Imagen003.png" alt="Molino SAG" class="w-full h-full object-cover group-hover:scale-105 transition-transform" onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1581092160607-ee22621dd758?auto=format&fit=crop&w=400&q=80'">
                </div>
                <div class="p-2 text-center text-xs font-bold truncate">Molino SAG</div>
            </div>

            <!-- Item 3 -->
            <div class="border border-black/10 rounded-lg overflow-hidden cursor-pointer group bg-neutral-100" onclick="openModal('Imagen005.png', 'Cristalizador USACH', 'Reactor especializado con control térmico e instrumentación directa.')">
                <div class="h-32 overflow-hidden relative bg-neutral-200">
                    <img src="Imagen005.png" alt="Cristalizador" class="w-full h-full object-cover group-hover:scale-105 transition-transform" onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1532187863486-abf9dbad1b69?auto=format&fit=crop&w=400&q=80'">
                </div>
                <div class="p-2 text-center text-xs font-bold truncate">Cristalizador USACH</div>
            </div>

            <!-- Item 4 -->
            <div class="border border-black/10 rounded-lg overflow-hidden cursor-pointer group bg-neutral-100" onclick="openModal('Imagen007.png', 'Experimento de Darcy', 'Banco hidráulico para estudio de fluidos en medios porosos.')">
                <div class="h-32 overflow-hidden relative bg-neutral-200">
                    <img src="Imagen007.png" alt="Darcy" class="w-full h-full object-cover group-hover:scale-105 transition-transform" onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1581091226825-a6a2a5aee158?auto=format&fit=crop&w=400&q=80'">
                </div>
                <div class="p-2 text-center text-xs font-bold truncate">Experimento Darcy</div>
            </div>

            <!-- Item 5 -->
            <div class="border border-black/10 rounded-lg overflow-hidden cursor-pointer group bg-neutral-100" onclick="openModal('Imagen008.png', 'Equipo Experimental U. de Chile', 'Cámara transparente con sensores para análisis electroquímico.')">
                <div class="h-32 overflow-hidden relative bg-neutral-200">
                    <img src="Imagen008.png" alt="U Chile" class="w-full h-full object-cover group-hover:scale-105 transition-transform" onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=400&q=80'">
                </div>
                <div class="p-2 text-center text-xs font-bold truncate">Cámara U. de Chile</div>
            </div>

            <!-- Item 6 -->
            <div class="border border-black/10 rounded-lg overflow-hidden cursor-pointer group bg-neutral-100" onclick="openModal('Imagen014.png', 'Columna AMINPRO', 'Sistema modular de gran altura para pruebas metalúrgicas.')">
                <div class="h-32 overflow-hidden relative bg-neutral-200">
                    <img src="Imagen014.png" alt="Aminpro" class="w-full h-full object-cover group-hover:scale-105 transition-transform" onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1579783902614-a3fb3927b675?auto=format&fit=crop&w=400&q=80'">
                </div>
                <div class="p-2 text-center text-xs font-bold truncate">Columna Aminpro</div>
            </div>

            <!-- Item 7 -->
            <div class="border border-black/10 rounded-lg overflow-hidden cursor-pointer group bg-neutral-100" onclick="openModal('Imagen006.png', 'Electrocelda Mistop®', 'Equipo para electrometalurgia enfocado en supresión de niebla.')">
                <div class="h-32 overflow-hidden relative bg-neutral-200">
                    <img src="Imagen006.png" alt="Mistop" class="w-full h-full object-cover group-hover:scale-105 transition-transform" onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1507679799987-c73779587ccf?auto=format&fit=crop&w=400&q=80'">
                </div>
                <div class="p-2 text-center text-xs font-bold truncate">Electrocelda Mistop</div>
            </div>

            <!-- Item 8 -->
            <div class="border border-black/10 rounded-lg overflow-hidden cursor-pointer group bg-neutral-100" onclick="openModal('Imagen010.png', 'Manifold Multilínea', 'Cilindro con múltiples llaves de paso para control de flujos.')">
                <div class="h-32 overflow-hidden relative bg-neutral-200">
                    <img src="Imagen010.png" alt="Manifold" class="w-full h-full object-cover group-hover:scale-105 transition-transform" onerror="this.onerror=null; this.src='https://images.unsplash.com/photo-1581092160607-ee22621dd758?auto=format&fit=crop&w=400&q=80'">
                </div>
                <div class="p-2 text-center text-xs font-bold truncate">Manifold Acrílico</div>
            </div>
        </div>
    </section>

    <!-- CONTACTO RÁPIDO -->
    <section id="contacto" class="py-12 px-4 max-w-xl mx-auto border-t border-black/10">
        <h2 class="text-xl font-bold uppercase tracking-wider text-center mb-6">Contacto</h2>
        <form id="contact-form" class="space-y-4">
            <div>
                <input type="text" required placeholder="Tu Nombre / Institución" class="w-full bg-neutral-50 border border-black/20 rounded-lg px-4 py-2.5 text-xs focus:outline-none focus:border-black">
            </div>
            <div>
                <input type="email" required placeholder="Correo electrónico" class="w-full bg-neutral-50 border border-black/20 rounded-lg px-4 py-2.5 text-xs focus:outline-none focus:border-black">
            </div>
            <div>
                <textarea rows="3" required placeholder="Detalles de tu requerimiento..." class="w-full bg-neutral-50 border border-black/20 rounded-lg px-4 py-2.5 text-xs focus:outline-none focus:border-black"></textarea>
            </div>
            <button type="submit" class="w-full bg-black text-white py-3 rounded-lg font-bold text-xs uppercase tracking-wider hover:bg-neutral-800 transition-all">
                Enviar Mensaje
            </button>
            <p id="form-success" class="hidden text-center text-xs text-emerald-600 font-semibold">¡Enviado con éxito!</p>
        </form>
    </section>

    <!-- FOOTER -->
    <footer class="bg-black text-white py-6 px-4 text-center text-xs">
        <p>© 2026 CUSTOMTECH. Equipos I+D.</p>
    </footer>

    <!-- MODAL (ZOOM DE IMAGEN) -->
    <div id="image-modal" class="fixed inset-0 z-50 bg-black/80 hidden items-center justify-center p-4">
        <div class="bg-white max-w-lg w-full rounded-xl overflow-hidden relative p-4">
            <button onclick="closeModal()" class="absolute top-3 right-3 w-8 h-8 bg-neutral-100 rounded-full flex items-center justify-center text-black font-bold z-10">
                <i class="fas fa-times"></i>
            </button>
            <div class="h-64 sm:h-80 bg-neutral-50 flex items-center justify-center mb-4 mt-2">
                <img id="modal-img" src="" alt="Detalle" class="max-h-full max-w-full object-contain">
            </div>
            <h3 id="modal-title" class="font-bold text-sm mb-1"></h3>
            <p id="modal-desc" class="text-xs text-neutral-600"></p>
        </div>
    </div>

    <!-- SCRIPT -->
    <script>
        const modal = document.getElementById('image-modal');
        const modalImg = document.getElementById('modal-img');
        const modalTitle = document.getElementById('modal-title');
        const modalDesc = document.getElementById('modal-desc');

        function openModal(imgSrc, title, desc) {
            modalImg.src = imgSrc;
            modalTitle.textContent = title;
            modalDesc.textContent = desc;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeModal() {
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        modal.addEventListener('click', (e) => {
            if (e.target === modal) closeModal();
        });

        const contactForm = document.getElementById('contact-form');
        const formSuccess = document.getElementById('form-success');
        contactForm.addEventListener('submit', (e) => {
            e.preventDefault();
            formSuccess.classList.remove('hidden');
            contactForm.reset();
            setTimeout(() => formSuccess.classList.add('hidden'), 4000);
        });
    </script>
</body>
</html>
