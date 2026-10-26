---
title: IProtectionManager class
second_title: Aspose.Slides dla Pythona przez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/iprotectionmanager/
---
## IProtectionManager klasa

Zarządzanie ochroną hasłem prezentacji.

Typ IProtectionManager udostępnia następujące elementy:

## Właściwości

| Property | Opis |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/pl/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Ta właściwość ma sens, jeśli prezentacja jest zabezpieczona hasłem.<br/>            Jeśli true, to właściwości dokumentu są zaszyfrowane w pliku prezentacji.<br/>            Jeśli false, to właściwości dokumentu są publiczne, podczas gdy prezentacja jest zaszyfrowana.<br/>            Odczyt/zapis **bool**. |
| [`is_encrypted`](/slides/python-net/pl/aspose.slides/iprotectionmanager/is_encrypted/) | Zwraca wartość wskazującą, czy ta instancja jest zaszyfrowana.<br/>            Tylko do odczytu **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/pl/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem i właściwości dokumentu <br/>            tego pliku są publiczne.<br/>            Wartość true oznacza, że tylko właściwości dokumentu są ładowane z zaszyfrowanego <br/>            pliku prezentacji bez użycia hasła.<br/>            Wartość false oznacza, że cała zaszyfrowana prezentacja jest ładowana z użyciem prawidłowego <br/>            hasła, a nie tylko właściwości dokumentu.<br/>            Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze false.<br/>            Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne, wartość właściwości jest zawsze false.<br/>            Jeśli PresentationEx.EncryptDocumentProperties jest true, to wartość właściwości IsOnlyDocumentPropertiesLoaded <br/>            jest zawsze false.<br/>            Tylko do odczytu **bool**. |
| [`is_write_protected`](/slides/python-net/pl/aspose.slides/iprotectionmanager/is_write_protected/) | Zwraca wartość wskazującą, czy ta prezentacja jest zabezpieczona przed zapisem.<br/>            Tylko do odczytu **bool**. |
| [`encryption_password`](/slides/python-net/pl/aspose.slides/iprotectionmanager/encryption_password/) | Zwraca hasło szyfrowania.<br/>            Tylko do odczytu **str**. |
| [`read_only_recommended`](/slides/python-net/pl/aspose.slides/iprotectionmanager/read_only_recommended/) | Zwraca lub ustawia zalecenie tylko do odczytu.<br/>            Odczyt/zapis **bool**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/pl/aspose.slides/iprotectionmanager/encrypt/#str) | Szyfruje Presentation przy użyciu określonego hasła. |
| [`remove_encryption(self)`](/slides/python-net/pl/aspose.slides/iprotectionmanager/remove_encryption/#) | Usuwa szyfrowanie. |
| [`set_write_protection(self, password)`](/slides/python-net/pl/aspose.slides/iprotectionmanager/set_write_protection/#str) | Ustawia ochronę przed zapisem dla tej prezentacji przy użyciu określonego hasła. |
| [`remove_write_protection(self)`](/slides/python-net/pl/aspose.slides/iprotectionmanager/remove_write_protection/#) | Usuwa ochronę przed zapisem dla tej prezentacji. |
| [`check_write_protection(self, password)`](/slides/python-net/pl/aspose.slides/iprotectionmanager/check_write_protection/#str) | Określa, czy prezentacja jest chroniona hasłem przed modyfikacją. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)