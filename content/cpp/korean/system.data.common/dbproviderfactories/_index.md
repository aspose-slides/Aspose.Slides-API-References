---
title: DbProviderFactories
second_title: Aspose.Slides for C++ API 참조
description: "DB 공급자 팩토리를 가져오는 API입니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 이 유형의 인스턴스를 스택에 생성하거나 operator new를 사용해서는 안 됩니다. 이렇게 하면 런타임 오류 또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하십시오."
type: docs
weight: 53
url: /ko/system.data.common/dbproviderfactories/
---
## DbProviderFactories 클래스

DB 공급자 팩토리를 가져오는 API입니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여 할당해야 합니다. 이 유형의 인스턴스를 스택에 생성하거나 operator new를 사용해서는 안 됩니다. 이렇게 하면 런타임 오류 또는 어설션 오류가 발생할 수 있습니다. 이 클래스를 항상 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하십시오.

```cpp
class DbProviderFactories
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | 이름으로 DB 공급자 팩토리를 가져옵니다. |

## 참고

* 네임스페이스 [System::Data::Common](../)
* 라이브러리 [Aspose.Slides](../../)