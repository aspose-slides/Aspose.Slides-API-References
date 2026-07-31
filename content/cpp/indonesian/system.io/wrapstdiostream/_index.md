---
title: WrapSTDIOStream()
second_title: Referensi API Aspose.Slides untuk C++
description: "Fungsi pembungkus untuk aliran mirip std::basic_istream."
type: docs
weight: 469
url: /id/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) fungsi


Fungsi pembungkus untuk aliran mirip std::basic_istream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | aliran mirip std::basic_istream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Mode pembungkus |

### Nilai Kembali

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) pembungkus

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) fungsi


Fungsi pembungkus untuk aliran mirip std::basic_ostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | aliran mirip std::basic_ostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Mode pembungkus |

### Nilai Kembali

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) pembungkus

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) fungsi


Fungsi pembungkus untuk aliran mirip std::basic_iostream.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | aliran mirip std::basic_iostream |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Mode pembungkus |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Posisi yang akan dipilih sebagai posisi baca dan tulis, jika berbeda |

### Nilai Kembali

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) pembungkus

## Lihat Juga

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)