---
title: Zip64Mode
second_title: Aspose.Slides for Android Java API 레퍼런스
description: OpenXML 파일에 ZIP64 형식 확장을 사용할 시점을 지정합니다.
type: docs
url: /ko/com.aspose.slides/zip64mode/
---
**상속:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

OpenXML 파일에 ZIP64 형식 확장을 사용할 시점을 지정합니다.

--------------------

OpenXML 파일은 압축되지 않은 파일 크기, 압축된 파일 크기 및 아카이브 전체 크기에 대해 4 GB(2^32 바이트) 제한과 아카이브 내 파일 수가 65,535(2^16-1)개로 제한된 ZIP 아카이브입니다. ZIP64 형식 확장은 이러한 제한을 2^64까지 늘립니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Never](#Never) | ZIP64 형식 확장을 사용하지 않습니다. |
| [IfNecessary](#IfNecessary) | 필요한 경우 ZIP64 형식 확장을 사용합니다. |
| [Always](#Always) | 항상 ZIP64 형식 확장을 사용합니다. |
### Never {#Never}
```
public static final int Never
```

ZIP64 형식 확장을 사용하지 않습니다.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

필요한 경우 ZIP64 형식 확장을 사용합니다.

### Always {#Always}
```
public static final int Always
```

항상 ZIP64 형식 확장을 사용합니다.