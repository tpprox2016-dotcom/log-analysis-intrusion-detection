# 🛡️ Guardian IDS - Brute Force Monitor

Script em Python para detecção de intrusão em tempo real, focado no monitoramento de logs de autenticação do Linux (`/var/log/auth.log`).

## 🚀 Como funciona
O sistema lê continuamente o arquivo de log e dispara um alerta visual sempre que detectar múltiplas falhas de login (Brute Force).

### 🛠️ Tecnologias
* Python 3
* Linux / WSL (Ubuntu)
* Logs do Sistema (`/var/log/auth.log`)

## 📸 Demonstração

### 1. Alerta de Segurança
![Alerta](Captura de tela 2024-11-20 182921.png)

### 2. Simulação de Ataque
![Ataque](Captura de tela 2024-11-20 182910.png)

### 3. Lógica do Código
![Codigo](Captura de tela 2024-11-20 182356.png)

## 📋 Execução
1. Inicie o monitor:
   ```bash
   sudo python3 guardian.py
