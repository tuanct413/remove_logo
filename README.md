# 🤖 Zalo Bot AI Watermark Remover (Vercel Serverless Edition)

Dự án Microservice API chuyên dụng cho Zalo Bot, tối ưu 100% cho Vercel Serverless (0% Vercel RAM / CPU).

## 🚀 Hướng dẫn Deploy lên Vercel trong 1 phút:

### Cách 1: Deploy bằng Vercel CLI (Nhanh nhất)
1. Tải Vercel CLI: `npm install -g vercel`
2. Mở thư mục `zalo-bot-vercel` và chạy lệnh:
   ```bash
   vercel --prod
   ```
3. Copy đường link URL Vercel được cấp (Ví dụ: `https://zalo-bot-ai.vercel.app`)

### Cách 2: Deploy qua GitHub Repository
1. Đẩy thư mục `zalo-bot-vercel` lên 1 GitHub Repository mới đặt tên là `zalo-bot-ai`.
2. Truy cập [vercel.com/new](https://vercel.com/new) ➡️ Chọn Repo `zalo-bot-ai` ➡️ Nhấn **Deploy**.

---

## 🔑 Biến môi trường (Environment Variables trên Vercel):
Điền các thông số sau tại mục **Settings -> Environment Variables** trên Vercel:

- `ZALO_BOT_TOKEN`: `<YOUR_ZALO_BOT_TOKEN>`
- `GROQ_API_KEY`: `<YOUR_GROQ_API_KEY>`

---

## 🌐 Điền Webhook URL vào trang Zalo Bot Creator:
Sau khi Deploy xong, bạn lấy Link Vercel điền vào trang [Zalo Bot Creator](https://zalo.me/s/botcreator/):

👉 **Webhook URL:** `https://<YOUR-VERCEL-DOMAIN>.vercel.app/webhook`
