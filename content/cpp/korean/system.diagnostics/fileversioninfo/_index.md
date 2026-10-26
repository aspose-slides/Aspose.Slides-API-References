---
title: FileVersionInfo
second_title: Aspose.Slides for C++ API 레퍼런스
description: "파일 버전에 대한 정보를 제공합니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용해서만 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하여 사용하십시오."
type: docs
weight: 1
url: /ko/system.diagnostics/fileversioninfo/
---
## FileVersionInfo 클래스

파일 버전에 대한 정보를 제공합니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수만 사용하여 할당해야 합니다. 스택에 이 타입의 인스턴스를 만들거나 operator new를 사용해서는 안 됩니다. 그렇게 하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있습니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고, 해당 포인터를 인수로 함수에 전달하여 사용하십시오.

```cpp
class FileVersionInfo
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | 제품 버전 필드를 가져옵니다. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | 파일 버전 정보를 가져옵니다; 구현되지 않았습니다. |

## 참조

* 네임스페이스 [System::Diagnostics](../)
* 라이브러리 [Aspose.Slides](../../)