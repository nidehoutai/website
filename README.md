# 你的後台 — 品牌 Landing Page

> 來交朋友的 AI 後勤夥伴 · [nidehoutai.com](https://nidehoutai.com)

陳昱嘉 Jason Chen 個人品牌「**你的後台**」的對外 Landing Page。

從家裡的冷凍空調廠開始,用 AI 把報價、文書、流程一個個自動化——
現在,把這套經驗帶給其他傳產老闆。

---

## 部署架構

```
nidehoutai.com (Gandi 註冊)
   ↓ DNS 託管
Cloudflare DNS
   ↓ 指向
GitHub Pages (本 repo · main 分支)
```

## 修改流程

```bash
git pull
# 編輯 index.html
git add index.html
git commit -m "update: 描述改了什麼"
git push
```

push 後 GitHub Pages 會自動部署,約 30-60 秒生效。

---

© 2026 你的後台 · 陳昱嘉 Jason Chen
