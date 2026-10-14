# Mixins Bien Toi Uu Css

Bài CodeGym 1557.

## Chạy
`npm ci`, `npm run build`, sau đó mở index.html. `npm run build:min` tạo CSS nén; `npm run watch` theo dõi thay đổi. PowerShell có thể dùng npm.cmd.

## Tái cấu trúc
Nguồn CSS trong đề: h1 32px, h2 28px, text #222, button nền đỏ và card trắng. Tách variables/mixins/typography/buttons/cards; giữ nguyên các thuộc tính từ ví dụ, dùng Nesting cho typography.

Dùng @use để gộp partials. CSS đã biên dịch được commit để có thể mở trang ngay.

## Đối chiếu
Mở original.html để xem bản CSS ban đầu. Kết quả biên dịch tại build-validation.json; kiểm tra computed styles và bố cục trước/sau tại validation.json.
