---
title: ProtectionManager class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/protectionmanager/
---
## ProtectionManager Klasse

Verwaltung des Kennwortschutzes für Präsentationen.

Der Typ ProtectionManager stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/de/aspose.slides/protectionmanager/encrypt_document_properties/) | Diese Eigenschaft ist sinnvoll, wenn die Präsentation passwortgeschützt ist.<br/>            Wenn true, dann sind die Dokumenteigenschaften in der Präsentationsdatei verschlüsselt.<br/>            Wenn false, dann sind die Dokumenteigenschaften öffentlich, während die Präsentation verschlüsselt ist.<br/>            Lesen/Schreiben **bool**. |
| [`is_encrypted`](/slides/python-net/de/aspose.slides/protectionmanager/is_encrypted/) | Gibt einen Wert zurück, der angibt, ob diese Instanz verschlüsselt ist.<br/>            Nur lesen **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/de/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei passwortgeschützt ist und die Dokument<br/>            eigenschaften dieser Datei öffentlich sind.<br/>            Der Wert true bedeutet, dass nur die Dokumenteigenschaften aus einer verschlüsselten<br/>            Präsentationsdatei ohne Verwendung des Passworts geladen werden.<br/>            Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen<br/>            Passwort geladen wird, nicht nur die Dokumenteigenschaften.<br/>            Wenn die Präsentation nicht verschlüsselt ist, ist der Eigenschaftswert immer false.<br/>            Wenn Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind, ist der Eigenschaftswert immer false.<br/>            Wenn Presentation.EncryptDocumentProperties true ist, ist der Wert von IsOnlyDocumentPropertiesLoaded<br/>            immer false.<br/>            Nur lesen **bool**. |
| [`is_write_protected`](/slides/python-net/de/aspose.slides/protectionmanager/is_write_protected/) | Gibt einen Wert zurück, der angibt, ob diese Präsentation schreibgeschützt ist.<br/>            Nur lesen **bool**. |
| [`encryption_password`](/slides/python-net/de/aspose.slides/protectionmanager/encryption_password/) | Gibt das Passwort zurück, das für die Verschlüsselung der Präsentation verwendet wird.<br/>            Nur lesen **str**. |
| [`read_only_recommended`](/slides/python-net/de/aspose.slides/protectionmanager/read_only_recommended/) | Liest oder setzt die Leseempfehlung.<br/>            Lesen/Schreiben **bool**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/de/aspose.slides/protectionmanager/encrypt/#str) | Verschlüsselt die Präsentation mit dem angegebenen Passwort. |
| [`remove_encryption(self)`](/slides/python-net/de/aspose.slides/protectionmanager/remove_encryption/#) | Entfernt die Verschlüsselung. |
| [`set_write_protection(self, password)`](/slides/python-net/de/aspose.slides/protectionmanager/set_write_protection/#str) | Setzt den Schreibschutz für diese Präsentation mit dem angegebenen Passwort. |
| [`remove_write_protection(self)`](/slides/python-net/de/aspose.slides/protectionmanager/remove_write_protection/#) | Entfernt den Schreibschutz für diese Präsentation. |
| [`check_write_protection(self, password)`](/slides/python-net/de/aspose.slides/protectionmanager/check_write_protection/#str) | Bestimmt, ob eine Präsentation passwortgeschützt ist, um modifiziert zu werden. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)