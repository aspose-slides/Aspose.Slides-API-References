---
title: WrapSTDIOStream()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ฟังก์ชันห่อหุ้มสำหรับสตรีมที่คล้าย std::basic_istream"
type: docs
weight: 469
url: /th/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) ฟังก์ชัน

ฟังก์ชันห่อหุ้มสำหรับสตรีมที่คล้าย std::basic_istream

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | สตรีมที่คล้าย std::basic_istream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | โหมดการห่อหุ้ม |

### Return Value

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) ตัวห่อ

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) ฟังก์ชัน

ฟังก์ชันห่อหุ้มสำหรับสตรีมที่คล้าย std::basic_ostream

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | สตรีมที่คล้าย std::basic_ostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | โหมดการห่อหุ้ม |

### Return Value

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) ตัวห่อ

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) ฟังก์ชัน

ฟังก์ชันห่อหุ้มสำหรับสตรีมที่คล้าย std::basic_iostream

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | สตรีมที่คล้าย std::basic_iostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | โหมดการห่อหุ้ม |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | ตำแหน่งที่ต้องการใช้เป็นตำแหน่งอ่านและเขียน หากแตกต่างกัน |

### Return Value

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) ตัวห่อ

## See Also

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)