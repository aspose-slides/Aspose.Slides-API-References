---
title: NativeLibrary
second_title: C++용 Aspose.Slides API 참조
description: 
type: docs
weight: 40
url: /ko/system.runtime.interopservices/nativelibrary/
---
## NativeLibrary 클래스




```cpp
class NativeLibrary
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static void [Free](./free/)(IntPtr) | 동적 라이브러리를 언로드합니다. |
| static IntPtr [GetExport](./getexport/)(IntPtr, const [String](../../system/string/)\&) | 지정된 라이브러리 항목의 주소를 가져옵니다. |
| static IntPtr [Load](./load/)(const [String](../../system/string/)\&) | 네이티브 동적 라이브러리를 로드합니다. 오류가 발생하면 예외를 발생시킵니다. |
| static **bool** [TryLoad](./tryload/)(const [String](../../system/string/)\&, IntPtr\&) | 네이티브 동적 라이브러리를 로드합니다. |
## 참고

* 네임스페이스 [System::Runtime::InteropServices](../)
* 라이브러리 [Aspose.Slides](../../)