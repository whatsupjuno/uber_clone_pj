- middleware는 양파껍질 같은 것이다!
  예를 들어 logger(morgan)는 모든 요청을 로깅하는 미들웨어, 우리 앱의 API로 무언가 할 때마다 이 미들웨어가 요청을 가로채서 요청을 기록하고 다음단계로 수행,
  helmet은 보안을 middleware, 요청이 올 때마다 요청을 잠시 멈추고 안전한지 검사한 다음에 다음 단계를 수행
