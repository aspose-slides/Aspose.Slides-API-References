---
title: IProtectionManager class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iprotectionmanager/
---
## IProtectionManager Klasse

Verwaltung des Kennwortschutzes für Präsentationen.

Der Typ IProtectionManager stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/de/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Diese Eigenschaft ist sinnvoll, wenn die Präsentation kennwortgeschützt ist.<br/>            Wenn wahr, dann sind die Dokumenteigenschaften in der Präsentationsdatei verschlüsselt.<br/>            Wenn falsch, dann sind die Dokumenteigenschaften öffentlich, während die Präsentation verschlüsselt ist.<br/>            Lesen/Schreiben **bool**. |
| [`is_encrypted`](/slides/python-net/de/aspose.slides/iprotectionmanager/is_encrypted/) | Gibt einen Wert zurück, der angibt, ob diese Instanz verschlüsselt ist.<br/>            Nur lesbar **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/de/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Diese Eigenschaft ist sinnvoll, wenn die Präsentationsdatei kennwortgeschützt ist und die Dokument<br/>            eigenschaften dieser Datei öffentlich sind.<br/>            Der Wert true bedeutet, dass nur die Dokumenteigenschaften aus einer verschlüsselten<br/>            Präsentationsdatei ohne Verwendung eines Kennworts geladen werden.<br/>            Der Wert false bedeutet, dass die gesamte verschlüsselte Präsentation mit dem richtigen<br/>            Kennwort geladen wird, nicht nur die Dokumenteigenschaften.<br/>            Wenn die Präsentation nicht verschlüsselt ist, ist der Eigenschaftswert immer false.<br/>            Wenn die Dokumenteigenschaften einer verschlüsselten Datei nicht öffentlich sind, ist der Eigenschaftswert immer false.<br/>            Wenn PresentationEx.EncryptDocumentProperties true ist, dann ist der Eigenschaftswert von IsOnlyDocumentPropertiesLoaded <br/>            immer false.<br/>            Nur lesbar **bool**. |
| [`is_write_protected`](/slides/python-net/de/aspose.slides/iprotectionmanager/is_write_protected/) | Gibt einen Wert zurück, der angibt, ob diese Präsentation schreibgeschützt ist.<br/>            Nur lesbar **bool**. |
| [`encryption_password`](/slides/python-net/de/aspose.slides/iprotectionmanager/encryption_password/) | Gibt das Verschlüsselungskennwort zurück.<br/>            Nur lesbar **str**. |
| [`read_only_recommended`](/slides/python-net/de/aspose.slides/iprotectionmanager/read_only_recommended/) | Liest oder setzt die Empfehlung für schreibgeschützt.<br/>            Lesen/Schreiben **bool**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/de/aspose.slides/iprotectionmanager/encrypt/#str) | Verschlüsselt die Präsentation mit dem angegebenen Kennwort. |
| [`remove_encryption(self)`](/slides/python-net/de/aspose.slides/iprotectionmanager/remove_encryption/#) | Entfernt die Verschlüsselung. |
| [`set_write_protection(self, password)`](/slides/python-net/de/aspose.slides/iprotectionmanager/set_write_protection/#str) | Setzt den Schreibschutz für diese Präsentation mit dem angegebenen Kennwort. |
| [`remove_write_protection(self)`](/slides/python-net/de/aspose.slides/iprotectionmanager/remove_write_protection/#) | Entfernt den Schreibschutz für diese Präsentation. |
| [`check_write_protection(self, password)`](/slides/python-net/de/aspose.slides/iprotectionmanager/check_write_protection/#str) | Bestimmt, ob eine Präsentation passwortgeschützt ist, um sie zu ändern. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)