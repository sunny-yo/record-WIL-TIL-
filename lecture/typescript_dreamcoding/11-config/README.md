# 타입스크립트 컴파일러

```
tsc --init    // tsconfig 파일 생성
tsc -w    // watch 모드 : ts파일 수정이 될 때마다 js로 컴파일
```

### tsconfig.json

> https://www.typescriptlang.org/tsconfig

```
프로젝트 구조 정리를 위한 설정

{
  "compilerOptions": {
    "rootDir": "./src",   // ts파일은 ./src 안에서만
    "outDir": "./build"   // 컴파일된 js파일은 ./build 안으로
  },
  "include": [],    // 컴파일해야하는 파일 경로 리스트로 작성
  "exclude": [],    // 컴파일에서 제외해야하는 파일 경로 리스트로 작성
}
```
