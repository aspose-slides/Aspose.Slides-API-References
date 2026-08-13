---
title: ConstructorInfo()
second_title: Aspose.Slides C++용 API 참조
description: 매개변수가 없는 생성자를 위해 ConstructorInfo 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 1
url: /ko/system.reflection/constructorinfo/constructorinfo/
---
## ConstructorInfo::ConstructorInfo(const String\&, std::function\<System::Object::ptr()>) 생성자

새 매개변수가 없는 생성자를 위해 [ConstructorInfo](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Reflection::ConstructorInfo::ConstructorInfo(const String &full_name, std::function<System::Object::ptr()> default_constructor)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| full_name | const [String](../../../system/string/)\& | name of the constructor |
| default_constructor | std::function\<[System::Object::ptr](../../../system/object/ptr/)()> | function pointer to the constructor |

## 참고

* Typedef [ptr](../../../system/object/ptr/)
* Class [String](../../../system/string/)
* Class [ConstructorInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)