---
title: WrapSTDIOStream()
second_title: Aspose.Slides for C++ API Referansı
description: "std::basic_istream benzeri akışlar için sarmalayıcı fonksiyon."
type: docs
weight: 469
url: /tr/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) fonksiyon

std::basic_istream benzeri akışlar için sarmalayıcı fonksiyon.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream benzeri akış |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Sarmalama modu |

### Dönüş Değeri

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) sarmalayıcı

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) fonksiyon

std::basic_ostream benzeri akışlar için sarmalayıcı fonksiyon.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream benzeri akış |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Sarmalama modu |

### Dönüş Değeri

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) sarmalayıcı

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) fonksiyon

std::basic_iostream benzeri akışlar için sarmalayıcı fonksiyon.

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream benzeri akış |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | Sarmalama modu |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | Okuma ve yazma konumu farklı ise tercih edilecek konum |

### Dönüş Değeri

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) sarmalayıcı

## Ayrıca Bakınız

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Sınıf [Stream](../stream/)
* Ad Alanı [System::IO](../)
* Library [Aspose.Slides](../../)