---
title: ProtectionManager class
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/protectionmanager/
---
## ProtectionManager klasa

Zarządzanie ochroną hasłem prezentacji.

Typ ProtectionManager udostępnia następujące elementy:

## Properties

| Property | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/pl/aspose.slides/protectionmanager/encrypt_document_properties/) | Ta właściwość ma sens, jeśli prezentacja jest zabezpieczona hasłem.<br/>            Jeśli true, to właściwości dokumentu są szyfrowane w pliku prezentacji.<br/>            Jeśli false, to właściwości dokumentu są publiczne, podczas gdy prezentacja jest zaszyfrowana.<br/>            Odczyt/zapis **bool**. |
| [`is_encrypted`](/slides/python-net/pl/aspose.slides/protectionmanager/is_encrypted/) | Zwraca wartość wskazującą, czy ta instancja jest zaszyfrowana.<br/>            Tylko do odczytu **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/pl/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem i właściwości dokumentu<br/>            tego pliku są publiczne.<br/>            Wartość true oznacza, że z zaszyfrowanego pliku prezentacji ładowane są tylko właściwości dokumentu bez użycia hasła.<br/>            Wartość false oznacza, że cała zaszyfrowana prezentacja jest ładowana przy użyciu prawidłowego hasła, a nie tylko właściwości dokumentu.<br/>            Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze false.<br/>            Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne, wartość właściwości jest zawsze false.<br/>            Jeśli Presentation.EncryptDocumentProperties jest true, to wartość właściwości IsOnlyDocumentPropertiesLoaded<br/>            jest zawsze false.<br/>            Tylko do odczytu **bool**. |
| [`is_write_protected`](/slides/python-net/pl/aspose.slides/protectionmanager/is_write_protected/) | Zwraca wartość wskazującą, czy ta prezentacja jest chroniona przed zapisem.<br/>            Tylko do odczytu **bool**. |
| [`encryption_password`](/slides/python-net/pl/aspose.slides/protectionmanager/encryption_password/) | Zwraca hasło używane do szyfrowania prezentacji.<br/>            Tylko do odczytu **str**. |
| [`read_only_recommended`](/slides/python-net/pl/aspose.slides/protectionmanager/read_only_recommended/) | Zwraca lub ustawia zalecenie tylko do odczytu.<br/>            Odczyt/zapis **bool**. |

## Methods

| Method | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/pl/aspose.slides/protectionmanager/encrypt/#str) | Szyfruje Presentation przy użyciu podanego hasła. |
| [`remove_encryption(self)`](/slides/python-net/pl/aspose.slides/protectionmanager/remove_encryption/#) | Usuwa szyfrowanie. |
| [`set_write_protection(self, password)`](/slides/python-net/pl/aspose.slides/protectionmanager/set_write_protection/#str) | Ustawia ochronę przed zapisem dla tej prezentacji przy użyciu podanego hasła. |
| [`remove_write_protection(self)`](/slides/python-net/pl/aspose.slides/protectionmanager/remove_write_protection/#) | Usuwa ochronę przed zapisem dla tej prezentacji. |
| [`check_write_protection(self, password)`](/slides/python-net/pl/aspose.slides/protectionmanager/check_write_protection/#str) | Określa, czy prezentacja jest zabezpieczona hasłem w celu modyfikacji. |


### See Also
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)