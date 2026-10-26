---
title: Details_FileNotFoundException
second_title: Riferimento API Aspose.Slides per C++
description: "L'eccezione che viene lanciata quando un tentativo di accedere a un file che non esiste sul disco fallisce. Non creare manualmente istanze di questa classe. Usa invece la classe FileNotFoundException. Non inserire mai le istanze della classe FileNotFoundException in System::SmartPtr."
type: docs
weight: 183
url: /it/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException classe


L'eccezione che viene lanciata quando un tentativo di accedere a un file che non esiste sul disco fallisce. Non creare manualmente istanze di questa classe. Usa invece la classe FileNotFoundException. Non inserire mai le istanze della classe FileNotFoundException in [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Restituisce il nome del file che causa questa eccezione. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## Vedi anche

* Classe [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Spazio dei nomi [System::IO](../)
* Libreria [Aspose.Slides](../../)