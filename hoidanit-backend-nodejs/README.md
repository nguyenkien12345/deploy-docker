----------------------------------------------------------------------------------------------------------
"build-src": "babel src -d build --copy-files",
=> Build toàn bộ file trong folder src ra một folder mới có tên là build
Trong đó:
-d: tên thư mục output
--copy-files: copy toàn bộ tất cả các file (ngoại trừ file js) như html, css,... (không tính js) vào folder output
----------------------------------------------------------------------------------------------------------
Gõ npx sequelize-cli db:migrate => Tạo các tabel trong database của chúng ta

