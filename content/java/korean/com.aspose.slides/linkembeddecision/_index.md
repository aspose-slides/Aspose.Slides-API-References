---
title: LinkEmbedDecision
second_title: Aspose.Slides Java API 레퍼런스
description: 저장 중 객체가 어떻게 처리되는지를 결정합니다.
type: docs
url: /ko/com.aspose.slides/linkembeddecision/
---
**상속:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

객체가 저장되는 동안 어떻게 처리될지를 결정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Link](#Link) | 객체가 외부에 저장되며 URL로 참조됩니다 |
| [Embed](#Embed) | 가능한 경우 객체가 생성 파일에 삽입되어야 합니다. |
| [Ignore](#Ignore) | 객체가 무시됩니다. |
### 링크 {#Link}
```
public static final int Link
```


객체가 외부에 저장되며 URL로 참조됩니다

### 삽입 {#Embed}
```
public static final int Embed
```


가능한 경우 객체가 생성 파일에 삽입되어야 합니다. 삽입이 불가능한 경우 GetUrl이 호출되고 결과에 따라 객체가 URL로 참조되거나 무시됩니다.

### 무시 {#Ignore}
```
public static final int Ignore
```


객체가 무시됩니다.