# nextjs

# Setup

## Cài đặt NextAuth
npm install next-auth @prisma/client @next-auth/prisma-adapter

## Thêm TailwindCSS
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

## Cấu hình Prisma
npx prisma generate
npx prisma migrate dev

# Run

## Cấu hình môi trường (.env)

## Cài đặt dependencies
npm install

## Thiết lập Prisma (Database ORM)
Chạy migration để tạo bảng trong database:
npx prisma migrate dev --name init
Tạo file Prisma Client (dùng để truy vấn DB):
npx prisma generate
(Tuỳ chọn) Mở Prisma Studio (UI để kiểm tra database):
npx prisma studio

## Chạy dự án
npm run dev
