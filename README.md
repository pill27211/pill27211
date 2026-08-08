<h2 align="center">Hi there, I'm Pillsun Jeong 👋</h2>
<p align="center">Node.js 생태계 중심의 백엔드를 지망하는 개발자입니다.<br>MSA 기반 분산 환경과 인프라 설계에 관심이 많고, 수많은 <b>'정답이 없는 문제'</b> 속에서 늘 <b>'정답에 가장 가까워질 수 있는 길'</b>을 쫓습니다.</p>

---

### 👨‍💻 About

- 🚀 창업을 목표로 한 3인 팀 프로젝트 **[Align](https://github.com/pill27211/align-retrospective)** 에서 **백엔드 설계 ~ 인프라 구축 전반**과 클라이언트 API 연동 기능 개발을 담당했습니다.
- ✍️ 백엔드 설계 과정과 트레이드오프, 경험들을 **[Align Tech 기술 블로그](https://yeohaenghage.kr)** 에 기록합니다.
- 📫 [![Gmail](https://img.shields.io/badge/pill272119@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:pill272119@gmail.com)

### 🛠 Tech Stack

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

### 📦 Featured

**[🧭 Align — 여행하게](https://github.com/pill27211/align-retrospective)** — 게스트하우스 예약·커뮤니티·여행 동행 매칭 플랫폼 (3인 팀 협업)
> 역할별 **4개 서버(REST · 실시간 · 업로드 · 워커)** 로 분리하고, **무상태 설계 · 결제/예약 정합성 · 실시간 피드 랭킹 · 관측성**을 처음부터 끝까지 설계. → [아키텍처 회고](https://github.com/pill27211/align-retrospective) · [서비스](https://yeohaenghage.com)
>
> Align을 설계하며 부딪힌 **쓰기 경로 성능**과 **동시성 정합성** 문제는, 아래 두 실험으로 분리해 끝까지 파고들어 검증했습니다.
>
> **└ [⚡ write-path-bench](https://github.com/pill27211/write-path-bench)** — 동기 vs BullMQ 비동기 쓰기 경로 벤치마크
> 동일 부하(k6 · Docker)에서 **처리량 4.03×↑ · p99 −64%** 실측. 결과·하네스·원본 측정치까지 재현.
>
> **└ [🔒 concurrency-correctness-lab](https://github.com/pill27211/concurrency-correctness-lab)** — 서버 동시성 정합성 실험실
> 레이스 컨디션 방어 4종(atomic · 비관적 · 낙관적 락) 비교 · 분산 락 멱등성 · fencing token.

**[🎮 AlgoWiki](https://github.com/pill27211/algowiki-backend)** — 게임화한 알고리즘 온라인 저지 (학교 졸업작품)
> hustoj 기반 OJ에 **퀘스트·재화·상점·인벤토리·복권 등 RPG 게임화 백엔드**를 C/C++·PHP·cron으로 설계·구현. → [개요·아키텍처·소스](https://github.com/pill27211/algowiki-backend)
>
> **└ [🧩 algowiki-problems](https://github.com/pill27211/algowiki-problems)** — 졸업작품을 위해 직접 출제한 **217문제 아카이브**
 → [웹으로 보기](https://pill27211.github.io/algowiki-problems/)

**[💬 Chat-east](https://github.com/pill27211/Chat-east)** — 실시간 메신저 (AlgoWiki 후속작)
> Socket.IO 기반 실시간 채팅에 **WebRTC 음성통화**와 **FCM 푸시**를 얹은 메신저. Node/Express · MySQL · Android(Java) 클라이언트.

### 🧩 Problem Solving

한때 **백준 온라인 저지에서 2,000+ 문제**를 풀 정도로 알고리즘에 빠진 적이 있습니다. 특히 **자료구조와 그래프**, 그중에서도 **트리** 문제를 가장 좋아했으며, **[개인 티스토리 블로그](https://pill27211.tistory.com/)** 에 이따금씩 풀이를 기록했습니다. 또한 대회 **[브실컵](https://u.acmicpc.net/37a41e24-925f-45c5-b0d2-6d492960aa08/%EB%B8%8C%EC%8B%A4%EC%BB%B5%EC%97%90%EB%94%94%ED%86%A0%EB%A6%AC%EC%96%BC.pdf)** 에서 **검수진**으로 참여해 문제 검수와 대회 운영에 기여한 경험이 있습니다. <br><br> 돌아보면 제 관심은 문제를 **푸는 것 → 검수하는 것 → 직접 출제하고 플랫폼을 운영하는 것**으로 자연스럽게 옮겨갔고, 그 끝에서 졸업작품으로 **게임화된 온라인 저지를 만들고 217문제를 직접 출제**하게 되었습니다. → **[AlgoWiki 문제 아카이브](https://pill27211.github.io/algowiki-problems/)**

이 저지를 만들며 **서버·DB·게임 경제 시스템**과 씨름했던 경험이, 알고리즘 문제 풀이에만 머물던 저를 **본격적으로 백엔드 개발로 이끈 결정적인 계기**가 되었습니다.

[![solved.ac tier](https://mazassumnida.wtf/api/v2/generate_badge?boj=pill27211)](https://solved.ac/profile/pill27211)

### ✍️ 기술 블로그 (Align Tech)

- [무상태(Stateless) 아키텍처는 도대체 뭔가요?](https://yeohaenghage.kr/backend/server_stateless/)
- [실시간 랭킹 시스템 — ZSET과 마이크로 배치](https://yeohaenghage.kr/backend/post_ranking/)
- [분산 시스템 관측성(Observability) 스택 구축기](https://yeohaenghage.kr/backend/monitoring/)
- [Zero Trust — "모든 입력은 유죄"라는 방어 설계](https://yeohaenghage.kr/backend/zero_trust_architecture_01/)
