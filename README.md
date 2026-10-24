# MỘC® — Coffee & Bakery (concept)

Landing page concept cho quán cà phê + bánh tại Sài Gòn. Theme **dark
roast editorial**: nền `#14100a`, bone `#f2e7d3`, accent crema `#d9a05b`,
chữ display serif kết hợp mono label.

> Trang concept minh hoạ — form/đặt bàn chưa gửi dữ liệu đi đâu cả.

## Chạy

Single-file HTML — mở thẳng `index.html`, hoặc:

```bash
npx serve .
```

## Kỹ thuật

- **Single-file HTML** — không bundler, toàn bộ trong một file
- **Espresso cup 3D procedural** (three.js r128, `LatheGeometry`) + hạt
  hơi nước bay, response theo chuột
- GSAP + ScrollTrigger + Lenis (CDN): loader đếm số → curtain → hero
  entrance, scroll scenes, custom cursor hai lớp (dot + label)
- Menu 8 món, mỗi món một SVG hoạt hình riêng; ticker marquee CSS thuần

## Cấu trúc commit

Lịch sử tái dựng theo thứ tự phát triển thật: khung + token → preloader +
cursor → header + hero → ticker + menu → story + visit + footer → toàn bộ
JS (3D + motion).
