---
title: get_SchemaInfo()
second_title: Aspose.Slides برای مرجع API C++
description: اطلاعات طرح‌واره‌ای را که به عنوان نتیجه اعتبارسنجی طرح‌واره به گرهٔ فعلی اختصاص داده شده است، برمی‌گرداند.
type: docs
weight: 196
url: /fa/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() روش

اطلاعات طرح‌واره‌ای را که به‌عنوان نتیجه‌ای از اعتبارسنجی طرح‌واره به گرهٔ فعلی اختصاص داده شده است، برمی‌گرداند.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### مقدار بازگشتی

یک شیء IXmlSchemaInfo شامل اطلاعات طرح‌واره برای گرهٔ فعلی است. [Schema](../../../system.xml.schema/) اطلاعات می‌تواند بر روی عناصر، ویژگی‌ها یا گره‌های متنی که مقدار [XmlReader::get_ValueType](../get_valuetype/) غیر-null داشته باشند، تنظیم شود. اگر گرهٔ فعلی یکی از انواع گرهٔ مذکور نباشد، یا اگر نمونهٔ [XmlReader](../) اطلاعات طرح‌واره را گزارش ندهد، این روش **nullptr** برمی‌گرداند. اگر این روش از یک شیء [XmlTextReader](../../xmltextreader/) یا [XmlValidatingReader](../../xmlvalidatingreader/) فراخوانی شود، همیشه **nullptr** برمی‌گرداند. این پیاده‌سازی‌های [XmlReader](../) اطلاعات طرح‌واره را از طریق روش get_SchemaInfo افشا نمی‌کنند.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* کلاس [XmlReader](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)