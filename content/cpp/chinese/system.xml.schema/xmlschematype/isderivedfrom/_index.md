---
title: IsDerivedFrom()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个值，指示指定的派生模式类型是否派生自指定的基模式类型。
type: docs
weight: 209
url: /zh/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) 方法


返回一个值，指示指定的派生模式类型是否派生自指定的基模式类型。

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | 要测试的派生 [XmlSchemaType](../)。 |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | 用于测试派生 [XmlSchemaType](../) 的基 [XmlSchemaType](../)。 |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | XmlSchemaDerivationMethod 值之一，表示要从测试中排除的类型派生方法。 |

### 返回值

**true** 如果派生类型派生自基类型；否则 **false**。

## 另见

* 枚举 [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlSchemaType](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)