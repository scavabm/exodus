# exodus
Exodus - Uma experiência de 'Calm Tech' desenhada para restaurar sua atenção, proteger seus dados e recompensar suas pausas em um mundo barulhento.
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EXODUS | O Refúgio Digital</title>
    <meta name="description" content="Uma experiência de Calm Tech e Web3 desenhada para restaurar sua atenção.">
    
    <!-- Tailwind CSS (via CDN para simplicidade no GitHub Pages) -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Fontes Google -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Amatic+SC:wght@400;700&family=Work+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
    
    <!-- Ícones Lucide -->
    <script src="https://unpkg.com/lucide@latest"></script>

    <!-- Configuração do Design System -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        paper: '#F5F3EF',
                        primary: '#2D3436',
                        action: '#5BC5C5',
                        organic: '#E8A87C',
                        sage: '#9FB8AD',
                        stone: '#A8A196'
                    },
                    fontFamily: {
                        hand: ['"Amatic SC"', 'cursive'],
                        sans: ['"Work Sans"', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body { background-color: #F5F3EF; color: #2D3436; }
        .smooth-scroll { scroll-behavior: smooth; }
    </style>
</head>
<body class="antialiased smooth-scroll">

    <!-- Header -->
    <header class="fixed w-full top-0 bg-paper/90 backdrop-blur-sm border-b border-organic/30 z-50">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center gap-2">
                <!-- Ícone Hexagon Simulado -->
                <i data-lucide="hexagon" class="text-organic w-8 h-8"></i>
                <span class="font-hand text-3xl font-bold tracking-widest text-primary">EXODUS</span>
            </div>
            <nav class="hidden md:flex gap-8">
                <a href="#solucao" class="font-medium hover:text-action transition-colors">Solução</a>
                <a href="#funcionalidades" class="font-medium hover:text-action transition-colors">Funcionalidades</a>
                <a href="#filosofia" class="font-medium hover:text-action transition-colors">Filosofia</a>
            </nav>
            <a href="#app" class="bg-action text-white px-6 py-2 rounded-full font-bold hover:opacity-90 transition-opacity text-sm">
                Acessar Refúgio
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="pt-32 pb-20 px-6">
        <div class="max-w-4xl mx-auto text-center">
            <span class="inline-block py-1 px-3 rounded-full bg-sage/20 text-sage text-xs font-bold tracking-wider mb-6">
                WEB3 • WELLNESS • PRIVACY
            </span>
            <h1 class="font-hand text-6xl md:text-8xl text-primary mb-6 leading-none">
                O Refúgio Digital que <br/><span class="text-action">Transforma Silêncio em Valor</span>
            </h1>
            <p class="font-sans text-xl md:text-2xl text-stone font-light mb-10 max-w-2xl mx-auto leading-relaxed">
                Uma experiência de 'Calm Tech' desenhada para restaurar sua atenção, proteger seus dados e recompensar suas pausas em um mundo barulhento.
            </p>
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <a href="#" class="bg-primary text-paper px-8 py-4 rounded-xl font-medium text-lg hover:bg-action transition-colors flex items-center justify-center gap-2">
                    Entrar no Santuário <i data-lucide="arrow-right" class="w-5 h-5"></i>
                </a>
                <a href="#como-funciona" class="border border-organic text-organic px-8 py-4 rounded-xl font-medium text-lg hover:bg-organic/10 transition-colors">
                    Entender a Economia
                </a>
            </div>
        </div>
    </section>

    <!-- Problema vs Solução -->
    <section id="solucao" class="py-20 bg-white/50 border-y border-organic/20">
        <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-16 items-center">
            <div>
                <h2 class="font-hand text-5xl text-primary mb-6">O Algoritmo do Ruído</h2>
                <p class="text-lg text-primary/80 mb-6 leading-relaxed">
                    A economia digital atual lucra com a sua distração. Algoritmos agressivos capturam sua atenção e monetizam seus dados privados, gerando esgotamento mental e ansiedade.
                </p>
                <ul class="space-y-4">
                    <li class="flex items-start gap-3">
                        <i data-lucide="x-circle" class="text-stone w-6 h-6 mt-1"></i>
                        <span class="text-stone">Monetização de dados pessoais</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <i data-lucide="x-circle" class="text-stone w-6 h-6 mt-1"></i>
                        <span class="text-stone">Design viciante e intrusivo</span>
                    </li>
                </ul>
            </div>
            <div class="bg-paper border border-organic rounded-3xl p-8 relative shadow-lg">
                <div class="absolute -top-4 -right-4 bg-action text-white px-4 py-1 rounded-full font-bold text-sm">NOVA ERA</div>
                <h3 class="font-hand text-4xl text-primary mb-4">A Resposta Exodus</h3>
                <p class="text-lg text-primary/80 mb-6">
                    Um dApp que utiliza Blockchain para incentivar o <strong>desconexionismo</strong>. Invertemos a lógica: aqui, você é pago para parar.
                </p>
                <div class="space-y-4">
                    <div class="flex items-center gap-3">
                        <div class="bg-action/20 p-2 rounded-lg text-action"><i data-lucide="shield"></i></div>
                        <div>
                            <strong class="block text-primary">Privacidade Radical</strong>
                            <span class="text-sm text-stone">Arquitetura Local-First. Seus dados, seu cofre.</span>
                        </div>
                    </div>
                    <div class="flex items-center gap-3">
                        <div class="bg-organic/20 p-2 rounded-lg text-organic"><i data-lucide="hourglass"></i></div>
                        <div>
                            <strong class="block text-primary">Pausa-para-Ganhar</strong>
                            <span class="text-sm text-stone">Minere $SILENCE meditando.</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Funcionalidades -->
    <section id="funcionalidades" class="py-20 px-6">
        <div class="max-w-6xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="font-hand text-5xl text-primary mb-4">Arquitetura do Silêncio</h2>
                <p class="text-stone max-w-xl mx-auto">Funcionalidades desenhadas para reduzir a carga cognitiva.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="bg-white p-8 rounded-2xl border border-stone/20 hover:border-action transition-colors group">
                    <i data-lucide="zap" class="w-10 h-10 text-organic mb-6 group-hover:scale-110 transition-transform"></i>
                    <h3 class="font-hand text-3xl mb-2">Zona de Silêncio</h3>
                    <p class="text-stone text-sm leading-relaxed">Timer de meditação minimalista. Cada minuto de foco gera tokens diretamente na sua carteira local.</p>
                </div>
                <!-- Card 2 -->
                <div class="bg-white p-8 rounded-2xl border border-stone/20 hover:border-action transition-colors group">
                    <i data-lucide="message-circle" class="w-10 h-10 text-organic mb-6 group-hover:scale-110 transition-transform"></i>
                    <h3 class="font-hand text-3xl mb-2">Consultor Filosófico</h3>
                    <p class="text-stone text-sm leading-relaxed">IA com personas Estoicas e Existencialistas para reflexão profunda, longe de chats superficiais.</p>
                </div>
                <!-- Card 3 -->
                <div class="bg-white p-8 rounded-2xl border border-stone/20 hover:border-action transition-colors group">
                    <i data-lucide="flower" class="w-10 h-10 text-organic mb-6 group-hover:scale-110 transition-transform"></i>
                    <h3 class="font-hand text-3xl mb-2">Jardim do Éter</h3>
                    <p class="text-stone text-sm leading-relaxed">Marketplace Web3. Troque seu silêncio por artefatos digitais (NFTs) exclusivos.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Diferenciais -->
    <section id="filosofia" class="py-20 bg-primary text-paper">
        <div class="max-w-4xl mx-auto px-6 text-center">
            <h2 class="font-hand text-5xl mb-12">Por que somos diferentes?</h2>
            
            <div class="grid md:grid-cols-3 gap-8 text-left">
                <div>
                    <strong class="block text-action text-xl mb-2 font-hand tracking-wide">01. Filosofia Calm Tech</strong>
                    <p class="text-stone text-sm font-light">Design visual orgânico, sem notificações invasivas. Tecnologia que respeita seu tempo.</p>
                </div>
                <div>
                    <strong class="block text-action text-xl mb-2 font-hand tracking-wide">02. Engenharia Ética</strong>
                    <p class="text-stone text-sm font-light">Proteção contra sistemas "Rogue". Priorizamos bem-estar humano sobre métricas de vício.</p>
                </div>
                <div>
                    <strong class="block text-action text-xl mb-2 font-hand tracking-wide">03. Governança Real</strong>
                    <p class="text-stone text-sm font-light">O token $SILENCE não é especulativo. Ele representa poder de voto no futuro do protocolo.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 border-t border-stone/20 text-center">
        <div class="flex justify-center items-center gap-2 mb-4 opacity-50">
            <i data-lucide="hexagon" class="w-6 h-6"></i>
            <span class="font-hand text-2xl font-bold">EXODUS</span>
        </div>
        <p class="text-stone text-xs">
            © 2024 Exodus Protocol. Construído com princípios de Engenharia de Tokens e Ética Web3.<br/>
            Engenheiro de Software Sênior e Lead Product Designer
        </p>
    </footer>

    <!-- Init Icons -->
    <script>
        lucide.createIcons();
    </script>
</body>
</html>
