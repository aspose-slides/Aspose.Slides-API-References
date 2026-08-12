---
title: BasicSTDIOStreamWrapper()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ใหม่ของ BasicSTDIOStreamWrapper.
type: docs
weight: 14
url: /th/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) constructor


สร้างอินสแตนซ์ใหม่ของ [BasicSTDIOStreamWrapper](../).

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | การอ้างอิงถึงสตรีม |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | โหมดการห่อหุ้ม |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | ตำแหน่งที่ต้องการเป็นตำแหน่งการอ่านและเขียน หากต่างกัน |

## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper\&) constructor


คอนสตรัคเตอร์คัดลอก ถูกลบ.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## ดูเพิ่มเติม

* Enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)