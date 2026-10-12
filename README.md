# Bài 2 — Đóng gói JAR và lưu Artifact

**Sinh viên:** Nguyễn Đăng Dương  
**Lớp:** CNTT2  
**Môn học:** IT209 — Session 11

Workflow chạy JUnit, tạo Spring Boot executable JAR bằng `./gradlew bootJar`, sau đó tải `build/libs/*.jar` lên GitHub Actions với tên artifact `app-jar`.

## Chạy cục bộ

```bash
./gradlew test bootJar
```

Trên Windows có thể chạy `gradlew.bat test bootJar`.

## Kiểm tra kết quả

Trong tab **Actions**, mở lần chạy thành công và kiểm tra mục **Artifacts** có `app-jar` để tải xuống.

