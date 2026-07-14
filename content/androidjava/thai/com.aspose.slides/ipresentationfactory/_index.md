---
title: IPresentationFactory
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อนุญาตให้สร้างงานนำเสนอผ่านอินเทอร์เฟซ COM
type: docs
url: /th/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

อนุญาตให้สร้างงานนำเสนอผ่านอินเทอร์เฟซ COM

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createPresentation()](#createPresentation--) | สร้างงานนำเสนอใหม่. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | สร้างงานนำเสนอใหม่พร้อมตัวเลือกการโหลดเพิ่มเติม |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | รับข้อมูลเกี่ยวกับงานนำเสนอในไฟล์ที่ระบุ. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | รับข้อมูลเกี่ยวกับงานนำเสนอในสตรีมที่ระบุ. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | อ่านงานนำเสนอที่มีอยู่จากอาร์เรย์ |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | อ่านงานนำเสนอที่มีอยู่จากอาร์เรย์พร้อมตัวเลือกการโหลดเพิ่มเติม |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | อ่านงานนำเสนอที่มีอยู่จากสตรีม |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | อ่านงานนำเสนอที่มีอยู่จากสตรีมพร้อมตัวเลือกการโหลดเพิ่มเติม |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | อ่านงานนำเสนอที่มีอยู่จากไฟล์ |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | อ่านงานนำเสนอที่มีอยู่จากสตรีมพร้อมตัวเลือกการโหลดเพิ่มเติม |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | ดึงข้อความดิบจากสไลด์ |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | ดึงข้อความดิบจากสไลด์ |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | ดึงข้อความดิบจากสไลด์ |

### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

สร้างงานนำเสนอใหม่.

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation) - งานนำเสนอใหม่

### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

สร้างงานนำเสนอใหม่พร้อมตัวเลือกการโหลดเพิ่มเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ตัวเลือกการโหลด |

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation) - งานนำเสนอใหม่

### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

รับข้อมูลเกี่ยวกับงานนำเสนอในไฟล์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ไฟล์งานนำเสนอ. |

**คืนค่า:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - ข้อมูลงานนำเสนอ

### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

รับข้อมูลเกี่ยวกับงานนำเสนอในสตรีมที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมงานนำเสนอ. |

**คืนค่า:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - ข้อมูลงานนำเสนอ.

### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

อ่านงานนำเสนอที่มีอยู่จากอาร์เรย์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | อาร์เรย์สำหรับอ่าน |

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation) - งานนำเสนอที่อ่าน

### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

อ่านงานนำเสนอที่มีอยู่จากอาร์เรย์พร้อมตัวเลือกการโหลดเพิ่มเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | อาร์เรย์สำหรับอ่าน |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ตัวเลือกการโหลด |

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation) - งานนำเสนอที่อ่าน

### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

อ่านงานนำเสนอที่มีอยู่จากสตรีม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมข้อมูลสำหรับอ่าน |

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation) - งานนำเสนอที่อ่าน

### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

อ่านงานนำเสนอที่มีอยู่จากสตรีมพร้อมตัวเลือกการโหลดเพิ่มเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมข้อมูลสำหรับอ่าน |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ตัวเลือกการโหลด |

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation) - งานนำเสนอที่อ่าน

### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

อ่านงานนำเสนอที่มีอยู่จากไฟล์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ชื่อไฟล์ |

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation) - งานนำเสนอที่อ่าน

### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

อ่านงานนำเสนอที่มีอยู่จากสตรีมพร้อมตัวเลือกการโหลดเพิ่มเติม

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ชื่อไฟล์ |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ตัวเลือกการโหลด |

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation) - งานนำเสนอที่อ่าน

### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

ดึงข้อความดิบจากสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| file | java.lang.String | ไฟล์อินพุต |
| mode | int | โหมดการสกัด |

**คืนค่า:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - อินสแตนซ์ของ PresentationText ที่มีอาร์เรย์ SlideText แสดงข้อความดิบของสไลด์

### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

ดึงข้อความดิบจากสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมข้อมูล |
| mode | int | โหมดการสกัด |

**คืนค่า:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - อินสแตนซ์ของ PresentationText ที่มีอาร์เรย์ SlideText แสดงข้อความดิบของสไลด์

### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

ดึงข้อความดิบจากสไลด์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมข้อมูล |
| mode | int | โหมดการสกัด |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | ตัวเลือกการโหลด |

**คืนค่า:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - อินสแตนซ์ของ PresentationText ที่มีอาร์เรย์ SlideText แสดงข้อความดิบของสไลด์