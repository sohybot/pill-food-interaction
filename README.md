# 💊AI-based Pill–Food Interaction Detection Platform AI 기반 알약·음식 상호작용 분석 플랫폼

## 프로젝트 개요
'찍먹'은 약물 이미지와 음식 이미지를 인식하여
잠재적인 약물–음식 상호작용 위험을 알려주는 AI 서비스입니다.
정보 접근이 어려운 사용자를 위한 직관적인 안전 가이드를 목표로 합니다.

## 문제 정의
- 약물–음식 상호작용 정보가 분산되어 있음
- 고령자 및 다약제 복용자의 오남용 위험 증가
- 기존 정보는 전문적이고 접근성이 낮음

## 해결 방법
- Azure Custom Vision 기반 알약 이미지 인식
- YOLO 기반 음식 이미지 인식
- 공공 데이터를 활용한 약물–음식 상호작용 DB 구축
- 위험도 단계화(Safe / Caution) 제공

## 시스템 아키텍처
<img width="576" height="275" alt="image" src="https://github.com/user-attachments/assets/6e5bdb86-7718-4899-a77a-c6d9c571092d" />


## 기술 스택
- Frontend: React
- Backend: FastAPI (Python)
- AI: Azure Custom Vision, YOLO
- Database: Azure Cosmos DB
- Infra: Azure App Service
<img width="623" height="340" alt="스크린샷 2026-01-08 114542" src="https://github.com/user-attachments/assets/c4fb6d69-3489-4259-9ccb-4cfc5123ba09" />

## 주요 성과
- 알약 인식 정확도 93% 이상
- 데이터 불균형 문제 해결을 위한 오버샘플링 적용
- 음식 6,000개 / 약물 3,000개 데이터 정제
<img width="1336" height="687" alt="image" src="https://github.com/user-attachments/assets/41403546-3e7e-498d-9e03-8e0b486e4b76" />
<img width="895" height="582" alt="image" src="https://github.com/user-attachments/assets/b23ea4c0-d1a7-4538-afec-572b1af614fb" />
<img width="628" height="623" alt="image" src="https://github.com/user-attachments/assets/4feec535-4a92-4fa9-9d69-44d6315e261a" />
<img width="583" height="607" alt="image" src="https://github.com/user-attachments/assets/9d7d0a28-7865-4c7a-a62f-fd4fd211369a" /><img width="564" height="700" alt="image" src="https://github.com/user-attachments/assets/bdaab86b-53b8-44a1-94a1-7608bcd19368" />


## 윤리 및 안전
- 개인정보 미수집
- 공신력 있는 데이터 출처만 사용
- 의료 진단 아님을 명시

## 한계점
- 실제 의료 행위를 대체하지 않음
- 공개 데이터 범위 내 분석

## 향후 개선
- 자동 데이터 파이프라인 구축
- 개인화 위험도 분석

## 담당 역할
- AI 모델 설계 및 데이터 정제
- 프론트엔드 UI 구현
- 데이터 수집 
- PM

