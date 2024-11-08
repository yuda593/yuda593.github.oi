
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Penjualan Produk Aqua Desa Limau Manis</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f5f5;
        }
        .container {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1 {
            color: #333;
            text-align: center;
            margin-bottom: 30px;
        }
        .chart-container {
            margin-top: 20px;
        }
        .data-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 30px;
        }
        .data-table th, .data-table td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: center;
        }
        .data-table th {
            background-color: #4682B4;
            color: white;
        }
        .data-table tr:nth-child(even) {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Data Penjualan Produk Aqua Desa Limau Manis</h1>
        
        <div class="chart-container">
            <canvas id="salesChart"></canvas>
        </div>

        <table class="data-table">
            <thead>
                <tr>
                    <th>Tahun</th>
                    <th>Jumlah Penjualan</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>2021</td>
                    <td>18,000</td>
                </tr>
                <tr>
                    <td>2022</td>
                    <td>19,000</td>
                </tr>
                <tr>
                    <td>2023</td>
                    <td>17,000</td>
                </tr>
            </tbody>
        </table>
    </div>

    <script>
        const ctx = document.getElementById('salesChart').getContext('2d');
        new Chart(ctx, {
            type: 'bar',
            data: {
                labels: ['2021', '2022', '2023'],
                datasets: [{
                    label: 'Jumlah Penjualan',
                    data: [18000, 19000, 17000],
                    backgroundColor: '#4682B4',
                    borderColor: '#4682B4',
                    borderWidth: 1
                }]
            },
            options: {
                responsive: true,
                scales: {
                    y: {
                        beginAtZero: true,
                        title: {
                            display: true,
                            text: 'Jumlah Penjualan'
                        }
                    },
                    x: {
                        title: {
                            display: true,
                            text: 'Tahun'
                        }
                    }
                },
                plugins: {
                    title: {
                        display: true,
                        text: 'Grafik Penjualan Produk Aqua Per Tahun'
                    }
                }
            }
        });
    </script>
</body>
</html>
<div class="explanation-container">

<p>Gambar tersebut menunjukkan data penjualan produk Aqua di Desa Limau Manis selama 3 tahun, yaitu 2021, 2022, dan 2023. Dari data tersebut, kita dapat melihat bahwa:</p>

<ul>

<li>Pada tahun 2021, penjualan produk Aqua mencapai 18.000 unit.</li>

<li>Pada tahun 2022, penjualan produk Aqua meningkat menjadi 19.000 unit.</li>

<li>Pada tahun 2023, penjualan produk Aqua diperkirakan akan menurun menjadi 17.000 unit.</li>

</ul>

</div>

<style>

.explanation-container {

width: 80%;

max-width: 800px;

margin: 0 auto;

padding: 20px;

font-size: 16px;

line-height: 1.5;

}


.explanation-container p {

margin-bottom: 20px;

}


.explanation-container ul {

list-style-type: disc;

margin-left: 20px;

}


.explanation-container li {

margin-bottom: 10px;

}

</style>
