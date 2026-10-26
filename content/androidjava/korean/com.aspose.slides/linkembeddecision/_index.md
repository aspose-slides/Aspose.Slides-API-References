---
title: LinkEmbedDecision
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 저장하는 동안 객체가 어떻게 처리되는지 결정합니다.
type: docs
url: /ko/com.aspose.slides/linkembeddecision/
---
**상속:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

저장하는 동안 객체가 처리되는 방식을 결정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Link](#Link) | Object는 외부에 저장되며 URL로 참조됩니다 |
| [Embed](#Embed) | Object는 가능한 경우 생성된 파일에 포함되어야 합니다 |
| [Ignore](#Ignore) | Object는 무시됩니다 |
### 링크 {#Link}
```
public static final int Link
```

Object는 외부에 저장되며 URL로 참조됩니다

### 포함 {#Embed}
```
public static final int Embed
```

Object는 가능한 경우 생성된 파일에 포함되어야 합니다. 임베딩이 불가능한 경우 GetUrl이 호출되고, 결과에 따라 object가 URL로 참조되거나 무시됩니다.

### 무시 {#Ignore}
```
public static final int Ignore
```

Object는 무시됩니다.