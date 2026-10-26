---
title: Details_FileNotFoundException
second_title: Referência da API Aspose.Slides para C++
description: "A exceção que é lançada quando uma tentativa de acessar um arquivo que não existe no disco falha. Nunca crie instâncias desta classe manualmente. Use a classe FileNotFoundException em vez disso. Nunca encapsule as instâncias da classe FileNotFoundException em System::SmartPtr."
type: docs
weight: 183
url: /pt/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException classe


A exceção que é lançada quando uma tentativa de acessar um arquivo que não existe no disco falha. Nunca crie instâncias desta classe manualmente. Use a classe FileNotFoundException em vez disso. Nunca encapsule as instâncias da classe FileNotFoundException em [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Obtém o nome do arquivo que causa esta exceção. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## Veja Também

* Classe [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Espaço de nomes [System::IO](../)
* Biblioteca [Aspose.Slides](../../)