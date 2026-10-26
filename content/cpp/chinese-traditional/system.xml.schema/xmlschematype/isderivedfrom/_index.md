---
title: IsDerivedFrom()
second_title: Aspose.Slides for C++ API 參考
description: 返回一個值，指示指定的衍生模式類型是否從指定的基礎模式類型衍生。
type: docs
weight: 209
url: /zh-hant/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType>, const SharedPtr<XmlSchemaType>&, XmlSchemaDerivationMethod) 方法

返回一個值，指示指定的衍生模式類型是否從指定的基礎模式類型衍生。

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)<[XmlSchemaType](../)> | 要測試的衍生 [XmlSchemaType](../)。 |
| baseType | const [SharedPtr](../../../system/sharedptr/)<[XmlSchemaType](../)>& | 用於測試衍生 [XmlSchemaType](../) 的基礎 [XmlSchemaType](../)。 |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | 表示要從測試中排除的類型衍生方法之一的 XmlSchemaDerivationMethod 值。 |

## 返回值

**true** 表示衍生類型是從基礎類型衍生的；否則，**false**。

## 另請參閱

* 列舉 [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlSchemaType](../)
* 命名空間 [System::Xml::Schema](../../)
* 函式庫 [Aspose.Slides](../../../)