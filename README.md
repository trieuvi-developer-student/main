# profile-main

## Music Player
- Mở tab **Tiện ích** và chọn **Music Player**.
- Upload file MP3 vào `assets/music/`.
- Mở `assets/js/data.js`, chỉnh mảng `musicTracks` theo mẫu có sẵn (đường dẫn tương đối từ thư mục gốc website).
- Có thể thêm `cover: 'assets/music/cover.jpg'` để dùng ảnh bìa cho từng bài.
- Trình phát có Play/Pause, bài trước/sau, tua, âm lượng, shuffle và repeat. Trình duyệt không tự phát nhạc khi chưa có thao tác của người dùng.
- Trên desktop, Music Player mở cạnh profile; trên điện thoại, nó hiển thị toàn màn hình và có nút quay lại.


## DORI AUDIO — macOS-inspired interface

The music workspace now uses a macOS-inspired glass window with:
- macOS traffic-light window controls.
- Animated aurora background and floating ambient light layers.
- Pointer-following radial light and subtle 3D card tilt on desktop.
- Emerald audio spectrum bars that animate while a track is playing.
- Responsive player layout for mobile screens.
- Reduced-motion support for visitors who prefer less animation.

Music files and playlist configuration remain unchanged: add MP3 files under `assets/music/` and edit `assets/js/data.js`.


## Responsive layout correction

- Wide desktop (1280px and above): profile column and music workspace appear side by side.
- Tablet and phone (1279px and below): the music workspace becomes full-screen; the profile and its navbar are hidden until the user returns to the profile.
- In wide desktop split mode, the profile navbar is pinned above the left profile column and compacted to prevent it floating in the center across both columns.
