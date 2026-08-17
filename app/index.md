<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Custom Web Server</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: #fafafa;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .card {
            background: white;
            border: 1px solid #e1e4e8;
            border-radius: 12px;
            padding: 32px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
            text-align: center;
            max-width: 400px;
        }

        h1 {
            color: #0969da;
            font-size: 1.5rem;
            margin-top: 0;
            margin-bottom: 12px;
        }

        p {
            font-size: 0.95rem;
            color: #57606a;
            line-height: 1.5;
            margin-bottom: 20px;
        }

        .status-badge {
            display: inline-block;
            background-color: #dafbe1;
            color: #1a7f37;
            padding: 4px 10px;
            font-size: 0.8rem;
            font-weight: 600;
            border-radius: 2em;
        }
    </style>
</head>

<body>
    <div class="card">
