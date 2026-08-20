---
title: HandleRepeatedSpaces
second_title: Aspose.Slides Java API 참조
description: Markdown 내보내기 중 반복되는 일반 공백 문자를 어떻게 처리할지 지정합니다.
type: docs
url: /ko/com.aspose.slides/handlerepeatedspaces/
---
**상속:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

반복되는 일반 공백 문자를 Markdown 내보내기 중 어떻게 처리할지 지정합니다.

## 필드

| 필드 | 설명 |
| --- | --- |
| [None](#None) | 모든 공백이 일반 공백 문자 그대로 보존되며 아무 변경도 없습니다. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | 두 개 이상의 연속된 일반 공백 시퀀스를 일반 공백 문자와 non-breaking space 엔터티(NBSP)를 번갈아가며 변환합니다. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | 두 개 이상의 연속된 일반 공백 시퀀스를 첫 번째 공백은 일반 공백 문자로 보존하고, 이후의 모든 공백을 non-breaking space 엔터티(NBSP)로 교체하여 변환합니다. |

### None {#None}
```
public static final int None
```

모든 공백이 일반 공백 문자 그대로 보존되며 아무 변화가 적용되지 않습니다. 여러 연속된 공백은 있는 그대로 내보내집니다.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

두 개 이상의 연속된 일반 공백 시퀀스를 일반 공백 문자와 non-breaking space 엔터티(NBSP)를 번갈아 가며 변환합니다. 첫 번째 공백은 항상 일반 공백으로 보존됩니다.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

두 개 이상의 연속된 일반 공백 시퀀스를 첫 번째 공백은 일반 공백 문자로 보존하고, 이후의 모든 공백을 non-breaking space 엔터티(NBSP)로 교체하여 변환합니다.