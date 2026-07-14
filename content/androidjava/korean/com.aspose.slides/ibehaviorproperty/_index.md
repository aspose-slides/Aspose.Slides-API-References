---
title: IBehaviorProperty
second_title: Java API 참조용 Aspose.Slides for Android
description: 애니메이션 동작에 대한 속성 유형을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ibehaviorproperty/
---```
public interface IBehaviorProperty
```

애니메이션 동작에 대한 속성 유형을 나타냅니다. 다음 목록은 https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx 및 https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx 에서 가져왔습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getValue()](#getValue--) | 속성 값 |
| [isCustom()](#isCustom--) | 이 속성이 사양에 정의된 미리 정해진 속성 목록에 포함되지 않는지 여부를 표시합니다: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
### getValue() {#getValue--}
```
public abstract String getValue()
```

속성 값

**반환값:**
java.lang.String
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```

이 속성이 사양에 정의된 미리 정해진 속성 목록에 포함되지 않는지 여부를 표시합니다: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**반환값:**
boolean