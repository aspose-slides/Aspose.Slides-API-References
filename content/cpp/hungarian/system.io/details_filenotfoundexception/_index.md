---
title: Details_FileNotFoundException
second_title: Aspose.Slides C++ API referenciája
description: "A kivétel, amely akkor kerül dobásra, amikor egy nem létező fájl elérésére tett kísérlet a lemezen meghiúsul. Soha ne hozzon létre példányokat ebből az osztályból kézzel. Használja helyette a FileNotFoundException osztályt. Soha ne csomagolja be a FileNotFoundException osztály példányait a System::SmartPtr-be."
type: docs
weight: 183
url: /hu/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException osztály


Az a kivétel, amely akkor kerül dobásra, amikor egy nem létező fájl elérésére tett kísérlet a lemezen meghiúsul. Soha ne hozzon létre példányokat ebből az osztályból kézzel. Használja helyette a FileNotFoundException osztályt. Soha ne csomagolja be a FileNotFoundException osztály példányait a [System::SmartPtr](../../system/smartptr/)-be.

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Lekéri a kivételt okozó fájl nevét. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |
## Lásd még

* Osztály [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Névtere [System::IO](../)
* Könyvtár [Aspose.Slides](../../)