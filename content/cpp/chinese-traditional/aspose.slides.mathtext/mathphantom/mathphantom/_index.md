---
title: MathPhantom()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的基礎數學元素來初始化 MathPhantom 類別的新實例。
type: docs
weight: 144
url: /zh-hant/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) constructor

使用指定的基礎數學元素來初始化 [MathPhantom](../) 類別的新實例。

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 基礎 [IMathElement](../../imathelement/)，其可見性和佈局將由 phantom 控制。此元素定義可能被隱藏或顯示的內容，同時仍會影響周圍數學的幾何對齊。 |

## 備註

phantom 元素用於保留或壓縮其基礎表達式的視覺空間，而不一定顯示它。它對應於 OMML 元素 **<m:phant>**。

範例：
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## 相關參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [MathPhantom](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)