---
title: XmlParserContext()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "เริ่มต้นอินสแตนซ์ใหม่ของคลาส XmlParserContext ด้วยค่า XmlNameTable, XmlNamespaceManager, xml:lang, และ xml:space ที่ระบุ."
type: docs
weight: 261
url: /th/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) คอนสตรัคเตอร์

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlParserContext](../) ด้วยค่า [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, และ **xml:space** ที่ระบุ.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) ที่ใช้เพื่อทำให้สตริงเป็นอะตอม หากเป็น **nullptr** จะใช้ตารางชื่อที่ใช้สร้าง **nsMgr** แทน สำหรับข้อมูลเพิ่มเติมเกี่ยวกับสตริงที่เป็นอะตอม ดูที่ [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) ที่ใช้สำหรับค้นหาข้อมูลเนมสเปส หรือ **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | ขอบเขต **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | ค่าชนิด XmlSpace ที่ระบุขอบเขต **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) คอนสตรัคเตอร์

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlParserContext](../) ด้วยค่า [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space**, และการเข้ารหัส.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) ที่ใช้เพื่อทำให้สตริงเป็นอะตอม หากเป็น **nullptr** จะใช้ตารางชื่อที่ใช้สร้าง **nsMgr** แทน สำหรับข้อมูลเพิ่มเติมเกี่ยวกับสตริงที่เป็นอะตอม ดูที่ [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) ที่ใช้สำหรับค้นหาข้อมูลเนมสเปส หรือ **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | ขอบเขต **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | ค่าชนิด XmlSpace ที่ระบุขอบเขต **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | ออบเจกต์ Encoding ที่ระบุการตั้งค่าการเข้ารหัส. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) คอนสตรัคเตอร์

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlParserContext](../) ด้วยค่า [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), base URI, **xml:lang**, **xml:space**, และค่า document type ที่ระบุ.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) ที่ใช้เพื่อทำให้สตริงเป็นอะตอม หากเป็น **nullptr** จะใช้ตารางชื่อที่ใช้สร้าง **nsMgr** แทน สำหรับข้อมูลเพิ่มเติมเกี่ยวกับสตริงที่เป็นอะตอม ดูที่ [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) ที่ใช้สำหรับค้นหาข้อมูลเนมสเปส หรือ **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | ชื่อของการประกาศประเภทเอกสาร. |
| pubId | const [String](../../../system/string/)\& | ตัวระบุสาธารณะ. |
| sysId | const [String](../../../system/string/)\& | ตัวระบุระบบ. |
| internalSubset | const [String](../../../system/string/)\& | ส่วนย่อย DTD ภายใน. ส่วนย่อย DTD นี้ใช้สำหรับการแก้ไขเอนทิตี ไม่ได้ใช้สำหรับการตรวจสอบความถูกต้องของเอกสาร. |
| baseURI | const [String](../../../system/string/)\& | base URI สำหรับส่วนของ XML (ตำแหน่งที่ส่วนนั้นถูกโหลด). |
| xmlLang | const [String](../../../system/string/)\& | ขอบเขต **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | ค่าชนิด XmlSpace ที่ระบุขอบเขต **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) คอนสตรัคเตอร์

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlParserContext](../) ด้วยค่า [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), base URI, **xml:lang**, **xml:space**, การเข้ารหัส, และค่า document type ที่ระบุ.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) ที่ใช้เพื่อทำให้สตริงเป็นอะตอม หากเป็น **nullptr** จะใช้ตารางชื่อที่ใช้สร้าง **nsMgr** แทน สำหรับข้อมูลเพิ่มเติมเกี่ยวกับสตริงที่เป็นอะตอม ดูที่ [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) ที่ใช้สำหรับค้นหาข้อมูลเนมสเปส หรือ **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | ชื่อของการประกาศประเภทเอกสาร. |
| pubId | const [String](../../../system/string/)\& | ตัวระบุสาธารณะ. |
| sysId | const [String](../../../system/string/)\& | ตัวระบุระบบ. |
| internalSubset | const [String](../../../system/string/)\& | ส่วนย่อย DTD ภายใน. DTD นี้ใช้สำหรับการแก้ไขเอนทิตี ไม่ได้ใช้สำหรับการตรวจสอบความถูกต้องของเอกสาร. |
| baseURI | const [String](../../../system/string/)\& | base URI สำหรับส่วนของ XML (ตำแหน่งที่ส่วนนั้นถูกโหลด). |
| xmlLang | const [String](../../../system/string/)\& | ขอบเขต **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | ค่าชนิด XmlSpace ที่ระบุขอบเขต **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | ออบเจกต์ Encoding ที่ระบุการตั้งค่าการเข้ารหัส. |

## ดูเพิ่มเติม

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)