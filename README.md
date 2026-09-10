Agricola
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AgroTech - Inovação e Sustentabilidade no Campo</title>
    <!-- Estilos CSS simples e modernos diretamente no HTML -->
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
        }

        /* Cabeçalho */
        header {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                        url('https://images.unsplash.com/photo-1500382017468-9049fed747ef?q=80&w=1000&auto=format&fit=crop') center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        header h1 {
            font-size: 2.8rem;
            margin-bottom: 15px;
        }

        header p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: 0 auto 20px auto;
        }

        .btn {
            display: inline-block;
            background-color: #2ecc71;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn:hover {
            background-color: #27ae60;
        }

        /* Seção Principal */
        .container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            margin-bottom: 40px;
            color: #1e5128;
        }

        /* Cards de Recursos */
        .cards {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .card {
            background: white;
            border-radius: 8px;
            padding: 25px;
            flex: 1 1 300px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            text-align: center;
        }

        .card h3 {
            color: #2e7d32;
            margin-bottom: 15px;
        }

        .icon {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        /* Rodapé */
        footer {
            background-color: #1e5128;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }

        footer a {
            color: #2ecc71;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <!-- Cabeçalho Principal -->
    <header>
        <h1>🌱 AgroTech: Tecnologias para o Campo</h1>
        <p>Soluções inteligentes, agricultura de precisão e gestão agrícola simplificada para aumentar sua produtividade.</p>
        <a href="#solucoes" class="btn">Conheça as Soluções</a>
    </header>

    <!-- Conteúdo do Site -->
    <main class="container">
        <h2 id="solucoes" class="section-title">Nossas Soluções Agrícolas</h2>

        <div class="cards">
            <!-- Card 1 -->
            <div class="card">
                <div class="icon">🛰️</div>
                <h3>Sensoriamento Remoto</h3>
                <p>Monitoramento de lavouras via satélite com índices vegetativos (NDVI) para detecção rápida de estresse hídrico e pragas.</p>
            </div>

            <!-- Card 2 -->
            <div class="card">
                <div class="icon">📡</div>
                <h3>Internet das Coisas (IoT)</h3>
                <p>Sensores em tempo real instalados no solo para controle automatizado de irrigação e dados meteorológicos precisos.</p>
            </div>

            <!-- Card 3 -->
            <div class="card">
                <div class="icon">📊</div>
                <h3>Gestão de Safras</h3>
                <p>Análise de dados de colheita, máquinas e insumos para otimizar custos e prever o rendimento de forma inteligente.</p>
            </div>
        </div>
    </main>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2026 AgroTech - Desenvolvido no GitHub Pages</p>
        <p>Acesse o repositório deste projeto no <a href="https://github.com" target="_blank">GitHub</a></p>
    </footer>

</body>
</html>
