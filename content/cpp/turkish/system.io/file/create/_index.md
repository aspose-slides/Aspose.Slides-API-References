---
title: Create()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen tampon boyutu ve seçenekleri kullanarak yeni bir dosya oluşturur (veya mevcut dosyanın üzerine yazar) ve dosyayı okuma ve yazma erişimi için açar.
type: docs
weight: 53
url: /tr/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) method

Belirtilen tampon boyutu ve seçenekleri kullanarak yeni bir dosya oluşturur (veya mevcut dosyanın üzerine yazar) ve dosyayı okuma ve yazma erişimi için açar.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Oluşturulacak veya üzerine yazılacak dosyanın yolu |
| bufferSize | **int32_t** | Dosyadan okuma ve dosyaya yazma sırasında tamponlanan bayt sayısı |
| options | [FileOptions](../../fileoptions/) | Dosyanın nasıl oluşturulacağını veya üzerine yazılacağını belirtir |

### Return Value

Belirtilen dosyayla ilişkili [FileStream](../../filestream/) nesnesine bir paylaşımlı işaretçi

## See Also

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)