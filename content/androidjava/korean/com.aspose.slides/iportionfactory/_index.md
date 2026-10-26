---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create test portions
type: docs
url: /ko/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

테스트 부분을 만들 수 있습니다

--------------------

COM 호환성을 위해
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createPortion()](#createPortion--) | 빈 텍스트 portion을 생성합니다. |
| [createPortion(String str)](#createPortion-java.lang.String-) | 지정된 문자열에서 텍스트 portion을 생성합니다. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | 지정된 portion 데이터를 사용하여 portion을 생성합니다. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


빈 텍스트 portion을 생성합니다.

**반환:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


지정된 문자열에서 텍스트 portion을 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | java.lang.String | String. |

**반환:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


지정된 portion 데이터를 사용하여 portion을 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | 사용할 portion. |

**반환:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.