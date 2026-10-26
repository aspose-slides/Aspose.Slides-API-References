---
title: ColorTranslator
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: "執行顏色轉換。此類別的物件應僅使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 System::SmartPtr 指標，並使用此指標將其作為參數傳遞給函式。"
type: docs
weight: 66
url: /zh-hant/system.drawing/colortranslator/
---
## ColorTranslator 類別


執行顏色轉換。此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。

```cpp
class ColorTranslator
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | 將指定的 HTML 顏色表示法轉換為等效的 [Color](../color/) 物件。 |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | 將指定的 [Windows](../../system.windows/) 顏色轉換為等效的 [Color](../color/) 物件。 |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | 將指定的 [Color](../color/) 物件轉換為等效 HTML 顏色的字串表示形式。 |

## 另請參閱

* 命名空間 [System::Drawing](../)
* 程式庫 [Aspose.Slides](../../)