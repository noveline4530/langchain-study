# 🚀 LangChain 학습 기록
이 저장소는 "**Udemy 강의 - LangChain 으로 LLM 기반 애플리케이션 개발하기**" 를 학습한 내용을 정리한 공간입니다.  
LangChain의 주요 개념부터 실습 프로젝트까지 **핵심 내용을 요약**하고, 직접 실험한 코드 및 인사이트를 공유합니다.

---

## 📌 학습 내용 요약

### 1️⃣ LangChain 기본 개념 정리
- **LLM과 LangChain**: 대규모 언어 모델(LLM)과 LangChain의 역할 이해  
- **체인(Chain)**: `LLMChain`, `SequentialChain`, `RetrievalChain` 등 주요 체인 개념 정리  
- **에이전트(Agent)**: `Zero-shot Agent`, `ReAct Agent`, `CSV Agent` 등 다양한 에이전트 구조 분석  
- **프롬프트 엔지니어링**  
  - **Few-shot 프롬프팅**, **Chain of Thought(CoT)**, **ReAct 프롬프팅** 실험  
  - LangChain의 **프롬프트 템플릿 활용** 및 최적화  

### 2️⃣ 데이터 처리 & 검색 증강 생성(RAG)
- **문서 로더(DocumentLoader) & 텍스트 스플리터(TextSplitter)**  
  - PDF, 웹페이지, 데이터베이스에서 텍스트 추출 및 가공  
- **벡터 저장소(Vector Store) & 검색 엔진**  
  - **FAISS & Pinecone**을 활용한 효율적인 검색 및 임베딩 저장  
- **RAG (Retrieval-Augmented Generation)**  
  - LangChain 기반의 **검색 증강 생성 시스템 구축**  

### 3️⃣ OpenAI API & 도구(Tools)
- **OpenAI API와 LangChain 통합**  
  - GPT 모델을 활용한 질의응답 시스템 구축  
- **Tool & Toolkit 활용**  
  - API 호출을 자동화하는 **LangChain Tools** 구성  

### 4️⃣ 실전 프로젝트 학습
- **Ice Breaker Agent**  
  - 입력된 이름으로 구글 검색 → 링크드인 & 트위터 데이터 수집 → **개인화된 Ice Breaker 메시지 생성**  
- **Documentation Helper**  
  - 특정 패키지 문서에서 **질의응답 기능을 제공하는 챗봇** 구현  
- **코드 통역기 (Slim Version of ChatGPT Code Interpreter)**  
  - 주어진 코드의 의미를 해석하고 설명하는 LangChain 기반 인터프리터  

---

## 🏆 학습하며 얻은 인사이트
- LangChain의 **내부 코드베이스 분석**을 통해 **체인과 에이전트 동작 방식 이해**  
- 벡터 저장소를 활용한 **빠르고 정확한 검색 증강 생성(RAG) 시스템 구축 방법 습득**  
- OpenAI API와 LangChain을 조합하여 **자동화된 AI 애플리케이션을 효과적으로 개발**하는 방법 탐색  
- **프롬프트 최적화 및 체인 구성 방법에 대한 실험 및 결과 분석**  
