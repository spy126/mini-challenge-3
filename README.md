# mini-challenge-3

A mini challenge of Node.js workshop - Week 3

## Chuẩn bị

```
# Clone project
git clone https://github.com/spy126/hello-socket.io

# Install dependency packages
npm install
```

## Yêu cầu

1. Hoàn thành API `/send` thỏa mãn các yêu cầu sau:

- Request được gửi tới với dạng sau: `/api?msg=Hello world`
- Nội dung trong query `msg` sẽ được gửi đi tới tất cả người dùng đang online và hiện được trên UI của ứng dụng.

2. Hoàn thiện tính năng hiện thị số người online bằng cách emit event với key là: `change total`. Kết quả được thay đổi trên giao diện thì được tính là hoàn thành.
