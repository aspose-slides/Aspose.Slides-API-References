---
title: FileStream()
second_title: Aspose.Slides para C++ Referência da API
description: Constrói uma nova instância da classe FileStream e a inicializa com os parâmetros especificados.
type: docs
weight: 1
url: /pt/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) construtor


Constrói uma nova instância da classe [FileStream](../) e a inicializa com os parâmetros especificados.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo a ser aberto. |
| mode | [FileMode](../../filemode/) | Especifica o modo no qual abrir o arquivo. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) construtor


Constrói uma nova instância da classe [FileStream](../) e a inicializa com os parâmetros especificados.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo a ser aberto. |
| mode | [FileMode](../../filemode/) | Especifica o modo no qual abrir o arquivo. |
| access | [FileAccess](../../fileaccess/) | O tipo de acesso solicitado. |
| share | [FileShare](../../fileshare/) | O tipo de acesso que outros objetos [FileStream](../) têm ao arquivo aberto. |
| buffer_size | **int32_t** | O número de bytes armazenados em buffer durante as operações de leitura e escrita. |
| options | [FileOptions](../../fileoptions/) | Opções adicionais. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) construtor


Constrói uma nova instância da classe [FileStream](../) e a inicializa com os parâmetros especificados.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo a ser aberto. |
| mode | [FileMode](../../filemode/) | Especifica o modo no qual abrir o arquivo. |
| access | [FileAccess](../../fileaccess/) | O tipo de acesso solicitado. |
| share | [FileShare](../../fileshare/) | O tipo de acesso que outros objetos [FileStream](../) têm ao arquivo aberto. |
| buffer_size | **int32_t** | O número de bytes armazenados em buffer durante as operações de leitura e escrita. |
| useAsync | **bool** | Especifica se deve usar I/O assíncrono ou I/O síncrono. |

## Observações



O sistema operacional subjacente pode não suportar I/O assíncrono. 

## FileStream::FileStream(const FileStream\&) construtor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Veja Também

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Classe [String](../../../system/string/)
* Classe [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)