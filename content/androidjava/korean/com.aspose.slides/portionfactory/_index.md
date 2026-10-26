---
title: PortionFactory
second_title: Android용 Aspose.Slides Java API 참조
description: 테스트 구간을 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/portionfactory/
---
**Inheritance:**  
상속:

**All Implemented Interfaces:**  
구현된 모든 인터페이스:
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

테스트 구간을 생성할 수 있습니다

--------------------

COM 호환성을 위해
## Constructors

| Constructor | Description |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |

## Methods

| Method | Description |
| --- | --- |
| [createPortion()](#createPortion--) | 빈 텍스트 구간을 생성합니다. |
| [createPortion(String str)](#createPortion-java.lang.String-) | 지정된 문자열에서 텍스트 구간을 생성합니다. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | 지정된 구간 데이터를 사용하여 구간을 생성합니다. |

### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```

### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```

빈 텍스트 구간을 생성합니다.

**Returns:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.

### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```

지정된 문자열에서 텍스트 구간을 생성합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | 문자열. |

**Returns:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.

### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```

지정된 구간 데이터를 사용하여 구간을 생성합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | 사용할 구간. |

**Returns:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.