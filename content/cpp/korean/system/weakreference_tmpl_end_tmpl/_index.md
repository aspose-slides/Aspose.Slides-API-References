---
title: WeakReference<>
second_title: Aspose.Slides for C++ API 참조
description: 객체를 참조하면서도 해당 객체가 삭제될 수 있도록 하는 약한 참조를 나타냅니다.
type: docs
weight: 1522
url: /ko/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> 클래스

객체를 참조하면서도 해당 객체가 삭제될 수 있도록 하는 약한 참조를 나타냅니다.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | 현재 WeakReference 객체가 참조하는 객체가 삭제되었는지 여부를 반환합니다. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | 현재 WeakReference 객체가 참조하고 있는 객체(대상)를 가져옵니다. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 현재 WeakReference 객체가 참조하고 있는 객체(대상)를 설정합니다. |
| [WeakReference](./weakreference/)() | 기본 생성자. |
| [WeakReference](./weakreference/)(std::nullptr_t) | nullptr 로부터의 생성자. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 지정된 객체를 참조하는 WeakReference 클래스의 새 인스턴스를 초기화합니다. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | 지정된 객체를 참조하는 WeakReference 클래스의 새 인스턴스를 초기화합니다. |
## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)