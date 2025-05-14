# 📘 Commit Message Guidelines

이 프로젝트는 Conventional Commits(https://www.conventionalcommits.org/) 형식을 따릅니다.

---

✅ 기본 형식<br><br>

`<type>(optional scope): <commit message>`

예시: <br>
feat(map): 인천 서구 GeoJSON 필터링 및 지도 분리 구현 <br>
fix(data): 누락된 정류장 좌표 보완 <br>
docs(readme): 프로젝트 실행 방법 문서화

---

🔖 커밋 타입(type)<br><br>

feat:      새로운 기능 추가 <br>
fix:       버그 수정 <br>
docs:      문서 수정 (README, 주석 등) <br>
style:     코드 포맷 수정 (기능 변화 없음) <br>
refactor:  기능 변경 없이 구조 개선 <br>
test:      테스트 코드 추가/수정 <br>
chore:     기타 작업 (빌드 설정, 폴더 정리 등) <br>
perf:      성능 개선 관련 변경

---

📍 스코프(scope) 예시<br><br>

map:            지도 및 folium 관련 작업 <br>
bus:            버스 정류장 데이터 관련 <br>
data:           CSV, GeoJSON 등 원본 데이터 처리 <br>
presentation:   발표용 파일 또는 시각화 결과물 관련 <br>
readme:         README 또는 문서 수정 <br>
notebook:       Jupyter Notebook 파일 작업 <br>

---

✍ 커밋 메시지 예시 <br><br>

feat(map): 인천 서구 지도 분리 기능 구현  <br>
feat(bus): 정류장 밀도 Choropleth 시각화 추가 <br>
fix(data): 정류장 누락된 위경도 보완 <br>
docs: README에 프로젝트 목적 추가 <br>
refactor: notebook 구조 리팩토링 및 폴더 정리 <br>

