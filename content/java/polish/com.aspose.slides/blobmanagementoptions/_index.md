---
title: BlobManagementOptions
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje opcje, które można użyć do zarządzania zasadami obsługi BLOB oraz innymi ustawieniami BLOB.
type: docs
url: /pl/com.aspose.slides/blobmanagementoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Reprezentuje opcje, które mogą być użyte do zarządzania zasadami obsługi BLOB oraz innymi ustawieniami BLOB.

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Tworzy nowe domyślne opcje zarządzania blobami. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | The root path where temporary files will be created. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | The root path where temporary files will be created. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Tworzy nowe domyślne opcje zarządzania blobami.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku lub strumienia – przez cały czas życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, ale źródło (strumień lub plik) nie może być zmieniane w czasie życia instancji Presentation.

**Zwraca:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku lub strumienia – przez cały czas życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, ale źródło (strumień lub plik) nie może być zmieniane w czasie życia instancji Presentation.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Ta właściwość określa, czy mogą być tworzone pliki tymczasowe podczas pracy z BLOB-ami, co znacznie zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików.

--------------------

Wszystkie pliki zostaną usunięte po zakończeniu pracy z prezentacją.

**Zwraca:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Ta właściwość określa, czy mogą być tworzone pliki tymczasowe podczas pracy z BLOB-ami, co znacznie zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików.

--------------------

Wszystkie pliki zostaną usunięte po zakończeniu pracy z prezentacją.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany jest systemowy katalog tymczasowy. Proces hostingowy powinien mieć uprawnienia do tworzenia tam plików i folderów.

**Zwraca:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany jest systemowy katalog tymczasowy. Proces hostingowy powinien mieć uprawnienia do tworzenia tam plików i folderów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y są ładowane do pamięci; dopiero po przekroczeniu tego limitu stosowane są alternatywne mechanizmy (np. pliki tymczasowe). Przechowywanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

--------------------

Ta właściwość jest ignorowana, jeśli \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) jest ustawiona na false, ponieważ wówczas pamięć jest jedyną dostępną lokalizacją przechowywania i ograniczenie użycia BLOB-ów w pamięci nie ma efektu.

--------------------

Domyślna wartość to 629 145 600 bajtów (600 MB).

--------------------

Można ustawić tę właściwość na zero, ale zostanie zarezerwowana niewielka minimalna ilość pamięci.

**Zwraca:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y są ładowane do pamięci; dopiero po przekroczeniu tego limitu stosowane są alternatywne mechanizmy (np. pliki tymczasowe). Przechowywanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

--------------------

Ta właściwość jest ignorowana, jeśli \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) jest ustawiona na false, ponieważ wówczas pamięć jest jedyną dostępną lokalizacją przechowywania i ograniczenie użycia BLOB-ów w pamięci nie ma efektu.

--------------------

Domyślna wartość to 629 145 600 bajtów (600 MB).

--------------------

Można ustawić tę właściwość na zero, ale zostanie zarezerwowana niewielka minimalna ilość pamięci.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |