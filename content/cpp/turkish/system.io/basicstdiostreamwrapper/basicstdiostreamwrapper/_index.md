---
title: BasicSTDIOStreamWrapper()
second_title: Aspose.Slides C++ API Referansı
description: BasicSTDIOStreamWrapper sınıfının yeni bir örneğini oluşturur.
type: docs
weight: 14
url: /tr/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) yapıcı


Yeni bir [BasicSTDIOStreamWrapper](../) örneği oluşturur.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | Akışa referans |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Sarılma modu |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | Okuma ve yazma konumu farklıysa tercih edilecek konum |

## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper\&) yapıcı


Kopya yapıcı. Silinmiş.

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## İlgili

* Enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)