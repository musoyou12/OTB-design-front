# OTB — Design Intelligence

AI-powered design research automation system.

## Live
- `/` — Interactive landing (Three.js particle system)
- `/demo` — Research Packet Viewer (AI analysis dashboard)

## What it does
브리프 입력 → AI가 경쟁사 분석 + UX 패턴 도출 + 바이브코딩 프롬프트 자동 생성

## Stack
**Frontend** Three.js / GLSL shader / Vanilla JS  
**Pipeline** Node.js + Python hybrid  
**AI** GPT Vision 14-axis labeling / Claude API  
**Automation** n8n / Playwright / Airflow  
**DB** PostgreSQL / pgvector

## Key metrics
- Research time: 12–18h → 2–3h
- Labeling accuracy: ~85%
