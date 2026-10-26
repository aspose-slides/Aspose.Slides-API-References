---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java – dokumentacja API
description: Obiekt binarny dużego rozmiaru (BLOB) to dane binarne przechowywane jako pojedyncza jednostka – np. BLOB może być dźwiękiem, wideo lub samą prezentacją.
type: docs
url: /pl/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Obiekt binarny dużego rozmiaru (BLOB) to dane binarne przechowywane jako pojedyncza jednostka – np. BLOB może być dźwiękiem, wideo lub samą prezentacją. Wykorzystuje się szereg technik optymalizujących zużycie pamięci podczas pracy z BLOB-ami – które już znajdują się w prezentacji lub są dodawane później programowo. Korzystając z [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) możesz zmienić różne aspekty zachowania związane z obsługą BLOB-ów dla czasu życia instancji [IPresentation](../../com.aspose.slides/ipresentation).

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

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku lub strumienia – podczas czasu życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, ale źródło (strumień lub plik) nie może być zmieniane w trakcie życia instancji Presentation. Oto przykład:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException zostanie rzucony, ponieważ plik pres.pptx jest zablokowany na cały czas życia obiektu Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // po zwolnieniu obiektu Presentation, plik jest odblokowany i może zostać usunięty
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Zwraca:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Ta właściwość określa, czy instancja klasy Presentation może być właścicielem źródła – pliku lub strumienia – podczas czasu życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność podczas pracy z BLOB-ami, ale źródło (strumień lub plik) nie może być zmieniane w trakcie życia instancji Presentation. Oto przykład:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException zostanie rzucony, ponieważ plik pres.pptx jest zablokowany na cały czas życia obiektu Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // po zwolnieniu obiektu Presentation, plik jest odblokowany i może zostać usunięty
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Ta właściwość określa, czy podczas pracy z BLOB-ami mogą być tworzone pliki tymczasowe, co znacząco zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików.

--------------------

Wszystkie pliki zostaną usunięte po zakończeniu pracy z prezentacją.

**Zwraca:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Ta właściwość określa, czy podczas pracy z BLOB-ami mogą być tworzone pliki tymczasowe, co znacząco zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików.

--------------------

Wszystkie pliki zostaną usunięte po zakończeniu pracy z prezentacją.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany jest systemowy katalog tymczasowy. Proces hostujący powinien mieć uprawnienia do tworzenia plików i folderów w tej lokalizacji.

**Zwraca:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany jest systemowy katalog tymczasowy. Proces hostujący powinien mieć uprawnienia do tworzenia plików i folderów w tej lokalizacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

--------------------

Ta właściwość jest ignorowana, jeśli \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) jest ustawiona na false, ponieważ wówczas pamięć jest jedyną dostępną lokalizacją przechowywania i ograniczanie użycia BLOB-ów w pamięci nie ma wpływu.

--------------------

Wartość domyślna to 629 145 600 bajtów (600 MB).

--------------------

Możesz ustawić tę właściwość na zero, ale nadal zostanie zarezerwowana niewielka minimalna ilość pamięci.

**Zwraca:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Określa maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań.

--------------------

Ta właściwość jest ignorowana, jeśli \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) jest ustawiona na false, ponieważ wówczas pamięć jest jedyną dostępną lokalizacją przechowywania i ograniczanie użycia BLOB-ów w pamięci nie ma wpływu.

--------------------

Wartość domyślna to 629 145 600 bajtów (600 MB).

--------------------

Możesz ustawić tę właściwość na zero, ale nadal zostanie zarezerwowana niewielka minimalna ilość pamięci.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |