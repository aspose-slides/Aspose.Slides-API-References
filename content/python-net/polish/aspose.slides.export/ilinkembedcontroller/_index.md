---
title: ILinkEmbedController class
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController klasa

Interfejs wywołania zwrotnego używany do określenia, jak obiekt powinien być przetwarzany podczas zapisywania.

Typ ILinkEmbedController udostępnia następujące elementy:

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/pl/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Określa, gdzie obiekt powinien zostać zapisany.<br/>            Ta metoda jest wywoływana raz dla każdego identyfikatora obiektu.<br/>            Nie ma gwarancji, że nie będzie dwóch obiektów o tych samych danych, semanticName i contentType, ale z różnym identyfikatorem. |
| [`get_url(self, id, referrer)`](/slides/python-net/pl/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Zwraca adres URL do zewnętrznego obiektu.<br/>            Ta metoda jest zawsze wywoływana, jeśli **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** zwrócił [`LinkEmbedDecision.LINK`](/slides/python-net/pl/aspose.slides.export/linkembeddecision/LINK) i może być wywołana, jeśli **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** zwrócił [`LinkEmbedDecision.EMBED`](/slides/python-net/pl/aspose.slides.export/linkembeddecision/EMBED), ale osadzenie jest niemożliwe.<br/>            Może być wywoływana wielokrotnie dla tego samego identyfikatora obiektu. |
| [`save_external(self, id, entity_data)`](/slides/python-net/pl/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Zapisuje zewnętrzny obiekt. |


### Zobacz także
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)