---
title: GetChildRows()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 관계를 통해 자식으로 간주되는 행들을 가져옵니다.
type: docs
weight: 27
url: /ko/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) 메서드

지정된 관계를 통해 자식으로 간주되는 행들을 가져옵니다.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | 부모 행과 자식 행 간의 관계를 지정하는 Relation 객체. |

### 반환값

[Array](../../../system/array/) 반환된 자식 행들.

## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DataRow](../)
* Class [DataRelation](../../datarelation/)
* Namespace [System::Data](../../)
* Library [Aspose.Slides](../../../)