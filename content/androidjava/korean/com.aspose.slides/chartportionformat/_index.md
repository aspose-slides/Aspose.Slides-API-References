---
title: ChartPortionFormat
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 이 클래스는 차트에 사용되는 차트 부분 서식 속성을 포함합니다.
type: docs
url: /ko/com.aspose.slides/chartportionformat/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**구현된 모든 인터페이스:**  
[com.aspose.slides.IChartPortionFormat](../../com.aspose.slides/ichartportionformat)  
```
public final class ChartPortionFormat extends BasePortionFormat implements IChartPortionFormat
```

이 클래스는 차트에 사용되는 차트 부분 서식 속성을 포함합니다. [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.

--------------------

이 클래스는 특정 부분에 정의된 텍스트 부분 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않아 대부분의 경우 "undefined" 의미의 값을 얻게 됨을 의미합니다.

상속을 포함한 실제 서식 매개변수 값을 얻으려면 [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) 메서드를 사용해야 하며, 이 메서드는 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 인스턴스를 반환합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환값:**  
long