---
title: IProtectionManager class
second_title: Aspose.Slides pro Python přes .NET API Referenci
description: 
type: docs
url: /cs/aspose.slides/iprotectionmanager/
---
## IProtectionManager třída

Presentation password protection management.

The IProtectionManager type exposes the following members:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/cs/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Tato vlastnost má smysl, pokud je prezentace chráněna heslem.<br/>            Pokud je true, pak jsou vlastnosti dokumentu šifrovány v souboru prezentace.<br/>            Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je šifrována.<br/>            Číst/zapisovat **bool**. |
| [`is_encrypted`](/slides/python-net/cs/aspose.slides/iprotectionmanager/is_encrypted/) | Získá hodnotu indikující, zda je tato instance šifrována.<br/>            Pouze ke čtení **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/cs/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu <br/>            tohoto souboru jsou veřejné.<br/>            Hodnota true znamená, že jsou z šifrovaného <br/>            souboru prezentace načteny pouze vlastnosti dokumentu bez použití hesla.<br/>            Hodnota false znamená, že je načtena celá šifrovaná prezentace s použitím správného <br/>            hesla, nikoli pouze vlastnosti dokumentu.<br/>            Pokud prezentace není šifrována, pak je hodnota vlastnosti vždy false.<br/>            Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné, pak je hodnota vlastnosti vždy false.<br/>            Pokud je PresentationEx.EncryptDocumentProperties true, pak je hodnota IsOnlyDocumentPropertiesLoaded <br/>            vždy false.<br/>            Pouze ke čtení **bool**. |
| [`is_write_protected`](/slides/python-net/cs/aspose.slides/iprotectionmanager/is_write_protected/) | Získá hodnotu indikující, zda je tato prezentace chráněna proti zápisu.<br/>            Pouze ke čtení **bool**. |
| [`encryption_password`](/slides/python-net/cs/aspose.slides/iprotectionmanager/encryption_password/) | Vrací šifrovací heslo.<br/>            Pouze ke čtení **str**. |
| [`read_only_recommended`](/slides/python-net/cs/aspose.slides/iprotectionmanager/read_only_recommended/) | Získá nebo nastaví doporučení pro pouze ke čtení.<br/>            Číst/zapisovat **bool**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/cs/aspose.slides/iprotectionmanager/encrypt/#str) | Zašifruje prezentaci zadaným heslem. |
| [`remove_encryption(self)`](/slides/python-net/cs/aspose.slides/iprotectionmanager/remove_encryption/#) | Odstraní šifrování. |
| [`set_write_protection(self, password)`](/slides/python-net/cs/aspose.slides/iprotectionmanager/set_write_protection/#str) | Nastaví ochranu proti zápisu pro tuto prezentaci se zadaným heslem. |
| [`remove_write_protection(self)`](/slides/python-net/cs/aspose.slides/iprotectionmanager/remove_write_protection/#) | Odstraní ochranu proti zápisu pro tuto prezentaci. |
| [`check_write_protection(self, password)`](/slides/python-net/cs/aspose.slides/iprotectionmanager/check_write_protection/#str) | Určí, zda je prezentace chráněna heslem proti úpravám. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)