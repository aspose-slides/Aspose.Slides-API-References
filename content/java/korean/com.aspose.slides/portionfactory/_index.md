---
title: PortionFactory
second_title: Aspose.Slides for Java API 레퍼런스
description: 테스트 구역을 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/portionfactory/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)  
```
public class PortionFactory implements IPortionFactory
```

테스트 구역을 생성하도록 허용합니다

--------------------

COM 호환성을 위해
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createPortion()](#createPortion--) | 빈 텍스트 구역을 생성합니다. |
| [createPortion(String str)](#createPortion-java.lang.String-) | 지정된 문자열에서 텍스트 구역을 생성합니다. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | 지정된 구역 데이터를 사용하여 구역을 생성합니다. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


빈 텍스트 구역을 생성합니다.

**반환:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


지정된 문자열에서 텍스트 구역을 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | java.lang.String | String. |

**반환:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


지정된 구역 데이터를 사용하여 구역을 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | 사용할 구역. |

**반환:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.