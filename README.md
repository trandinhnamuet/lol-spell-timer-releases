# LOL Spell Timer

Cửa sổ nhỏ luôn nổi trên game để đếm ngược phép bổ trợ và chiêu cuối (R) của 5 địch, có **tự bắt Flash** bằng tiếng và minimap.

## Tải về

**[Tải bản mới nhất](https://github.com/trandinhnamuet/lol-spell-timer-releases/releases/latest)**: tải `LOL.Spell.Timer.exe`, để vào thư mục bất kỳ rồi chạy. Không cần cài Python.

1. Trong LMHT: **Cài đặt → Video → Chế độ cửa sổ: Không viền (Borderless)**.
2. Chạy exe. Lần đầu cần mạng để tải ảnh tướng và ảnh phép (~3 MB) từ Data Dragon của Riot vào thư mục `cache/` cạnh exe.

## Tự cập nhật

Từ v1.2.0, khi có bản mới nhãn **⬆** hiện trên thanh tiêu đề. Bấm vào, đọc ghi chú, bấm **Cập nhật**: app tải bản mới, kiểm SHA-256, thay file rồi tự khởi động lại. Có thể kiểm tra thủ công trong **⚙ → Kiểm tra cập nhật**.

## An toàn tài khoản

App không đọc bộ nhớ game, không chèn DLL, không giả lập phím. Dữ liệu địch lấy từ Live Client Data API chính thức của Riot (`127.0.0.1:2999`). Tự bắt Flash chỉ nghe âm thanh hệ thống và chụp vùng minimap trên màn hình. Riot cho phép đếm ngược bấm tay; tính năng tự bắt Flash là tùy chọn, tắt mặc định.
