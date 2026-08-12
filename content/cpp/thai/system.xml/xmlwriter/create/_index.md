---
title: Create()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ XmlWriter ใหม่โดยใช้ชื่อไฟล์ที่ระบุ.
type: docs
weight: 469
url: /th/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) method

สร้างอินสแตนซ์ [XmlWriter](../) ใหม่โดยใช้ชื่อไฟล์ที่ระบุ

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | ไฟล์ที่คุณต้องการเขียนไป. [XmlWriter](../) สร้างไฟล์ที่เส้นทางที่ระบุและเขียนเป็นไวยากรณ์ข้อความ XML 1.0. **outputFileName** ต้องเป็นเส้นทางของระบบไฟล์. |

### Return Value

วัตถุ [XmlWriter](../)

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) method

สร้างอินสแตนซ์ [XmlWriter](../) ใหม่โดยใช้ชื่อไฟล์และอ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/)

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | ไฟล์ที่คุณต้องการเขียนไป. [XmlWriter](../) สร้างไฟล์ที่เส้นทางที่ระบุและเขียนเป็นไวยากรณ์ข้อความ XML 1.0. **outputFileName** ต้องเป็นเส้นทางของระบบไฟล์. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | อ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/) ที่ใช้กำหนดค่าการตั้งค่าสำหรับอินสแตนซ์ [XmlWriter](../) ใหม่. หากเป็น **nullptr** จะใช้ [XmlWriterSettings](../../xmlwritersettings/) ที่มีการตั้งค่าเริ่มต้น. หาก [XmlWriter](../) ถูกใช้ร่วมกับเมธอด XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) คุณควรใช้ค่า XslCompiledTransform::get_OutputSettings เพื่อรับอ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/) ที่มีการตั้งค่าที่ถูกต้อง. สิ่งนี้ทำให้แน่ใจว่าอ็อบเจกต์ [XmlWriter](../) ที่สร้างขึ้นมีการตั้งค่าผลลัพธ์ที่ถูกต้อง. |

### Return Value

วัตถุ [XmlWriter](../)

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) method

สร้างอินสแตนซ์ [XmlWriter](../) ใหม่โดยใช้สตรีมที่ระบุ

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่คุณต้องการเขียนไป. [XmlWriter](../) เขียนไวยากรณ์ข้อความ XML 1.0 และต่อท้ายไปยังสตรีมที่ระบุ. |

### Return Value

วัตถุ [XmlWriter](../)

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) method

สร้างอินสแตนซ์ [XmlWriter](../) ใหม่โดยใช้สตรีมและอ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/)

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | สตรีมที่คุณต้องการเขียนไป. [XmlWriter](../) เขียนไวยากรณ์ข้อความ XML 1.0 และต่อท้ายไปยังสตรีมที่ระบุ. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | อ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/) ที่ใช้กำหนดค่าการตั้งค่าสำหรับอินสแตนซ์ [XmlWriter](../) ใหม่. หากเป็น **nullptr** จะใช้ [XmlWriterSettings](../../xmlwritersettings/) ที่มีการตั้งค่าเริ่มต้น. หาก [XmlWriter](../) ถูกใช้ร่วมกับเมธอด XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) คุณควรใช้ค่า XslCompiledTransform::get_OutputSettings เพื่อรับอ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/) ที่มีการตั้งค่าที่ถูกต้อง. สิ่งนี้ทำให้แน่ใจว่าอ็อบเจกต์ [XmlWriter](../) ที่สร้างขึ้นมีการตั้งค่าผลลัพธ์ที่ถูกต้อง. |

### Return Value

วัตถุ [XmlWriter](../)

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) method

สร้างอินสแตนซ์ [XmlWriter](../) ใหม่โดยใช้ TextWriter ที่ระบุ

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter ที่คุณต้องการเขียนไป. [XmlWriter](../) เขียนไวยากรณ์ข้อความ XML 1.0 และต่อท้ายไปยัง TextWriter ที่ระบุ. |

### Return Value

วัตถุ [XmlWriter](../)

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) method

สร้างอินสแตนซ์ [XmlWriter](../) ใหม่โดยใช้ TextWriter และอ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/)

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter ที่คุณต้องการเขียนไป. [XmlWriter](../) เขียนไวยากรณ์ข้อความ XML 1.0 และต่อท้ายไปยัง TextWriter ที่ระบุ. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | อ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/) ที่ใช้กำหนดค่าการตั้งค่าสำหรับอินสแตนซ์ [XmlWriter](../) ใหม่. หากเป็น **nullptr** จะใช้ [XmlWriterSettings](../../xmlwritersettings/) ที่มีการตั้งค่าเริ่มต้น. หาก [XmlWriter](../) ถูกใช้ร่วมกับเมธอด XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) คุณควรใช้ค่า XslCompiledTransform::get_OutputSettings เพื่อรับอ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/) ที่มีการตั้งค่าที่ถูกต้อง. สิ่งนี้ทำให้แน่ใจว่าอ็อบเจกต์ [XmlWriter](../) ที่สร้างขึ้นมีการตั้งค่าผลลัพธ์ที่ถูกต้อง. |

### Return Value

วัตถุ [XmlWriter](../)

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) method

สร้างอินสแตนซ์ [XmlWriter](../) ใหม่โดยใช้ [Text::StringBuilder](../../../system.text/stringbuilder/) ที่ระบุ

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) ที่จะเขียนไป. เนื้อหาที่ [XmlWriter](../) เขียนจะถูกต่อท้ายไปยัง [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Return Value

วัตถุ [XmlWriter](../)

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) method

สร้างอินสแตนซ์ [XmlWriter](../) ใหม่โดยใช้อ็อบเจกต์ [Text::StringBuilder](../../../system.text/stringbuilder/) และ [XmlWriterSettings](../../xmlwritersettings/)

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) ที่จะเขียนไป. เนื้อหาที่ [XmlWriter](../) เขียนจะถูกต่อท้ายไปยัง [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | อ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/) ที่ใช้กำหนดค่าการตั้งค่าสำหรับอินสแตนซ์ [XmlWriter](../) ใหม่. หากเป็น **nullptr** จะใช้ [XmlWriterSettings](../../xmlwritersettings/) ที่มีการตั้งค่าเริ่มต้น. หาก [XmlWriter](../) ถูกใช้ร่วมกับเมธอด XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) คุณควรใช้ค่า XslCompiledTransform::get_OutputSettings เพื่อรับอ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/) ที่มีการตั้งค่าที่ถูกต้อง. สิ่งนี้ทำให้แน่ใจว่าอ็อบเจกต์ [XmlWriter](../) ที่สร้างขึ้นมีการตั้งค่าผลลัพธ์ที่ถูกต้อง. |

### Return Value

วัตถุ [XmlWriter](../)

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) method

สร้างอินสแตนซ์ [XmlWriter](../) ใหม่โดยใช้อ็อบเจกต์ [XmlWriter](../) ที่ระบุ

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | อ็อบเจกต์ [XmlWriter](../) ที่คุณต้องการใช้เป็นตัวเขียนพื้นฐาน. |

### Return Value

อ็อบเจกต์ [XmlWriter](../) ที่ห่อหุ้มอ็อบเจกต์ [XmlWriter](../) ที่ระบุ

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) method

สร้างอินสแตนซ์ [XmlWriter](../) ใหม่โดยใช้อ็อบเจกต์ [XmlWriter](../) และ [XmlWriterSettings](../../xmlwritersettings/) ที่ระบุ

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | อ็อบเจกต์ [XmlWriter](../) ที่คุณต้องการใช้เป็นตัวเขียนพื้นฐาน. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | อ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/) ที่ใช้กำหนดค่าการตั้งค่าสำหรับอินสแตนซ์ [XmlWriter](../) ใหม่. หากเป็น **nullptr** จะใช้ [XmlWriterSettings](../../xmlwritersettings/) ที่มีการตั้งค่าเริ่มต้น. หาก [XmlWriter](../) ถูกใช้ร่วมกับเมธอด XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) คุณควรใช้ค่า XslCompiledTransform::get_OutputSettings เพื่อรับอ็อบเจกต์ [XmlWriterSettings](../../xmlwritersettings/) ที่มีการตั้งค่าที่ถูกต้อง. สิ่งนี้ทำให้แน่ใจว่าอ็อบเจกต์ [XmlWriter](../) ที่สร้างขึ้นมีการตั้งค่าผลลัพธ์ที่ถูกต้อง. |

### Return Value

อ็อบเจกต์ [XmlWriter](../) ที่ห่อหุ้มอ็อบเจกต์ [XmlWriter](../) ที่ระบุ

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)