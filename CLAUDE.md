# 와이어트 + 리더스유치원 프로젝트 현황

## 사장님이 해야 할 것 (우선순위 순)

### 1. Cloudflare 도메인 연결 (두 사이트 모두)

**와이어트 (www.wyatt.kr):**
1. https://dash.cloudflare.com → "Add a site" → `wyatt.kr` 추가 → Free 플랜
2. 네임서버를 Cloudflare가 알려주는 값으로 가비아에서 변경
3. Workers & Pages → `wyatt-seocho` → Custom domains → `wyatt.kr` + `www.wyatt.kr` 추가

**리더스유치원 (www.dongtan-kids.kr):**
1. https://dash.cloudflare.com → "Add a site" → `dongtan-kids.kr` 추가 → Free 플랜
2. 네임서버를 Cloudflare가 알려주는 값으로 가비아에서 변경
3. Workers & Pages → `leaders-dongtan` → Custom domains → `dongtan-kids.kr` + `www.dongtan-kids.kr` 추가

### 2. 도메인 연결 후 할 것
- 네이버 서치어드바이저 등록 (두 사이트 모두)
- Google Search Console 등록
- 네이버 플레이스 등록 (두 사이트 모두)
- Google Business Profile 등록

### 3. 콘텐츠 교체
- 리더스유치원: 실제 유치원 사진으로 이미지 교체 (assets/ 폴더)
- 와이어트: 실제 학원 사진으로 이미지 교체
- Formspree 실제 ID 교체 (상담 폼 활성화)

### 4. 바이럴 (중기)
- 런즈(learns.academy), 영유랭킹(youngu.kr) 플랫폼 등록
- 네이버 블로그 체험단 리뷰 확보
- 맘카페 바이럴

---

## 기술 현황 (완료)

| 사이트 | URL | GitHub | 키워드 | 상태 |
|--------|-----|--------|--------|------|
| 와이어트 | wyatt-seocho.pages.dev | riverboy1210/wyatt-seocho | 717회 | 배포완료 |
| 리더스유치원 | leaders-dongtan.pages.dev | riverboy1210/leaders-dongtan | 791회 | 배포완료 |

## 범용 템플릿v2
- 위치: `33.서울 및 경기.../00.범용템플릿v2(AEO강화)/`
- A형(영어유치원) + B형(일반유치원) 지원
- 새 사이트 제작 시 15분 내 완성 가능

## PPT 보고서
- 위치: `34.와이어트/와이어트_SEO_AEO_보고서.pptx`
