---
title: TemplateContext
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 템플릿 엔진용 모델 객체 인터페이스를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/templatecontext/
---
**상속:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

템플릿 엔진용 모델 객체 인터페이스를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | 자식 템플릿 컨텍스트를 생성합니다. |
| [getObject()](#getObject--) | 모델 객체를 반환합니다. |
| [getOutput()](#getOutput--) | 호스트 문서의 출력 요소 컬렉션을 반환합니다. |
| [getLocal()](#getLocal--) | 현재 템플릿 컨텍스트의 로컬 스토리지를 반환합니다. |
| [getGlobal()](#getGlobal--) | 호스트 문서의 전역 스토리지를 반환합니다. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

자식 템플릿 컨텍스트를 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| subModel | TSubModel | 자식 모델 객체. |

**반환:**
[TemplateContext](../../com.aspose.slides/templatecontext) - 주어진 모델과 부모의 출력 컬렉션 및 전역 스토리지를 가진 새로운 템플릿 컨텍스트.
### getObject() {#getObject--}
```
public final TObject getObject()
```

모델 객체를 반환합니다. 읽기 전용 Object.

**반환:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

호스트 문서의 출력 요소 컬렉션을 반환합니다. 읽기 전용 [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**반환:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

현재 템플릿 컨텍스트의 로컬 스토리지를 반환합니다. 읽기 전용 [Storage](../../com.aspose.slides/storage).

**반환:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

호스트 문서의 전역 스토리지를 반환합니다. 읽기 전용 [Storage](../../com.aspose.slides/storage).

**반환:**
[Storage](../../com.aspose.slides/storage)