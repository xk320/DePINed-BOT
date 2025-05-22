# DePINed BOT

## Requiremnets

- 确保已安装 Python3.9 或更高版本以及 pip。

## Instalation

1. **克隆仓库:**
   ```bash
   https://github.com/xk320/DePINed-BOT.git
   ```
   ```bash
   cd DePINed-BOT
   ```

2. **安装依赖:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## 配置

- **在项目目录中找到文件 accounts.json 。accounts.json 格式示例：:
  ```bash
  [
      {
          "Email": "your_email_address 1",
          "Password": "your_password 1"
      },
      {
          "Email": "your_email_address 2",
          "Password": "your_password 2"
      }
  ]
  ```

- **proxy.txt：项目目录中找到文件 proxy.txt 。proxy.txt格式的示例：:
  ```bash
    http://账号:密码@ip:port # 默认 HTTP代理.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## 运行

```bash
python bot.py #or python3 bot.py
```
