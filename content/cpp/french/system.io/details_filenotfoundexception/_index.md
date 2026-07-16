---
title: Details_FileNotFoundException
second_title: Référence de l'API Aspose.Slides pour C++
description: "L'exception qui est levée lorsqu'une tentative d'accéder à un fichier qui n'existe pas sur le disque échoue. Ne créez jamais d'instances de cette classe manuellement. Utilisez la classe FileNotFoundException à la place. N'enveloppez jamais les instances de la classe FileNotFoundException dans System::SmartPtr."
type: docs
weight: 183
url: /fr/system.io/details_filenotfoundexception/
---
## Détails_FileNotFoundException classe


L'exception qui est levée lorsqu'une tentative d'accès à un fichier qui n'existe pas sur le disque échoue. Ne créez jamais d'instances de cette classe manuellement. Utilisez la classe FileNotFoundException à la place. N'enveloppez jamais les instances de la classe FileNotFoundException dans [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Obtient le nom du fichier qui provoque cette exception. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |
## Voir aussi

* Classe [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)