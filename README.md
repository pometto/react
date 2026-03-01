# react
React + Vite + TypeScript starter repo test

Kısa açıklama
Bu repo, Vite + React + TypeScript ile hızlı başlamak için minimal bir starter şablonudur. Geliştirme, test ve basit CI örneği içerir.

Özellikler
- Vite dev server (HMR)
- TypeScript yapılandırması hazır
- React 18, fonksiyonel bileşen ve temel stil dosyaları
- Örnek GitHub Actions CI workflow (opsiyonel)

Başlarken (lokalde)
1. Klonla:
   git clone <repo-url>
2. Bağımlılıkları yükle:
   npm install
3. Geliştirme sunucusunu başlat:
   npm run dev
4. Prod build:
   npm run build
5. Üretim sunucusu (yerel test):
   npm run preview

Scriptler (package.json)
- dev: Vite development server
- build: Vite production build
- preview: Yerel olarak build sonucu önizleme
- lint/test: (isteğe göre ekle)

Projeyi GitHub’a koyarken
- README, LICENSE (örn. MIT), .gitignore ekle
- CI çalıştırmak istersen .github/workflows/ci.yml ekle
- Deploy için Vercel/Netlify/Cloudflare Pages tercih edilebilir

İleri adımlar / öneriler
- React Router ekle (SPA rota yönetimi)
- State yönetimi: Zustand / Redux Toolkit / Recoil
- Styling: Tailwind CSS veya styled-components
- Test: Jest + React Testing Library veya Vitest
- Type checking: CI içine `npm run build` veya `tsc --noEmit` ekle
- Lint & format: ESLint + Prettier entegre et

License
MIT
