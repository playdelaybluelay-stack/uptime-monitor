# uptime-monitor

서비스 상태와 가동 시간을 관측하고,
운영 및 복구 과정을 검증하기 위한 프로젝트입니다.

## Status

초기 저장소 골격을 구성하는 단계입니다.
실행 가능한 모니터링 애플리케이션과 배포 구성은 아직 구현 중입니다.

## Scope

- 서비스 상태 확인과 uptime 기록
- 운영 인프라 구성 및 복구 실험
- 실행·운영 절차의 코드 및 문서화

## Project Structure

```text
uptime-monitor/
 ├── app/ 
 ├── infra/
 │   ├── hetzner/
 │   └── aws-lab/
 ├── platform/
 │   ├── compose/
 │   └── k8s/
 ├── ops/
 │   ├── runbooks/
 │   ├── postmortems/
 │   ├── adr/
 │   └── evidence/
 └── .github/workflows/