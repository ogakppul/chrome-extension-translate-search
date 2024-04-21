# 빌드 방법
nodejs 21이상 설치

```bash
npm install -g webpack
npm install webpack --save-dev
npm run build
```
(빌드 방법은 https://github.com/ogakppul/chrome-extension-typescript-starter를 참고)
빌드가 완료되면 dist 폴더에 저장됨.
chrome에서 개발자 모드를 키고 dist 폴더를 로드하면 끝

# Translate and Search (Chrome Extension)

![GitHub](https://img.shields.io/github/license/34j/chrome-extension-translate-search)

A browser extension that when navigating to a url that contains the parameter `q` or `p`

- blocks navigating
- then translates the content of the parameter `q` and `p`
- then navigates back to the modified url.

## Tested

- Google Search
- Google Scholar
- DuckDuckGo
- Yahoo Search
- Microsoft Bing

## 日本語の説明

パラメータ`q`または`p`を含むurlにナビゲートしたときに、ナビゲートをブロックし、パラメータ`q`と`p`の内容を翻訳し、再びナビゲートするブラウザ拡張機能です。
