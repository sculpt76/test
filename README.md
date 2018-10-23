# 협동조합 모델

기존 협동조합 모델에 탈중앙화를 위하여 코인 이코노미를 적용할 수 있을 수 있을까?
상품의 유통 과정에 블럭체인을 적용하고 생산, 유통, 소비에 보상으로 코인을 지급하는 방식입니다.

## 목적
- 조합원과 생산자가 최소한의 유통과정 없이 직접 거래하는 모델 
- 생산자와 소비자 구분없이 진정한 협동조합이 이루어지도록 하고 싶습니다.

## Goal
- 결제 : Blockchain 기술을 통해 중간 유통부분을 최대한 생략
- 서버 : IPFS(InterPlanetary File System)를 이용해 협동조합에서 최소한의 개입만 있을 것입니다. IPFS 는 탈중앙화 파일 시스템 입니다
- 쇼핑몰 : 중간 전달자 뿐 아니라 MD의 개입도 들어내는 것이 목표 입니다. 
           쇼핑이 이루어지면 보상으로 포인트 개념의 코인이 지급되고
           후기를 쓰면 더 많은 코인이 지급됩니다
           이를 위해 알고리즘을 개발중에 있습니다
- 큐레이션 : 큐레이션 역시 중간 전달자 없이 소비자와 생산자로 결정되도록 구성됩니다

## Team

- 한근혁


## Roadmap

#### 1. Adagio
> 침착하게 느리게

- 백서 작성
- Coin 발행 (Ethereum 기반)
- Smart Contract

#### 2. Andante
> 모데라토보다 조금 느리게

- 쇼핑몰 개발 : Site
- 보상모델 개발 : 상품평, 사용기, 판매량, 구매량등

#### 3. Presto
> 매우 빠르게

- Blockchain 처리 속도 개선

## Action - 0.1 version

![new mockup 1](https://user-images.githubusercontent.com/44389221/47355508-7e11d280-d6fc-11e8-8147-6dad040ae754.png)

1. OOO 소비자 주문
  - from : 소비자
  - to : 협동조합 서버
2. 상품 결제를 위한 Smart Contract 생성
  - from : 협동조합 서버
  - to : Blockchain
3. 상품 결제
  - from : 소비자
  - to : Blockchain
4. 설정된 분류에 따른 분배
  - from : Smart Contract
  - to : 생산자
  - to : 창고
  - to : 운송자
  - to : Blockchain 에 결제 완료 Flag 설정
5. 결제 완료 확인
  - from : 협동조합서버
  - to : Blockchain
6. 소비자 제공
  - from : 생산자, 창고, 운송자
  - to : 소비자
  
## Action - 0.2 version

![img_5045](https://user-images.githubusercontent.com/897510/40751422-a4d3e3f8-649d-11e8-8546-70d297aa9b2e.jpg)

> Action 정리 해주세요

## Support
- 이 프로젝트는 이더리운연구회(http://www.etherstudy.net) 의 도움을 받고 있습니다

