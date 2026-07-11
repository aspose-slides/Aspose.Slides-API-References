---
title: IBlobManagementOptions
second_title: Aspose.Slides для Android через Java API Reference
description: Binary Large Object (BLOB) — это бинарные данные, хранящиеся как единый объект, то есть BLOB может быть аудио, видео или сама презентация.
type: docs
url: /ru/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Binary Large Object (BLOB) — это бинарные данные, хранящиеся как единый объект, то есть BLOB может быть аудио, видео или сама презентация. При работе с BLOB применяются различные техники оптимизации потребления памяти — BLOB может уже находиться в презентации или быть добавлен позже программно. С помощью [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) вы можете изменить различные аспекты поведения при работе с BLOB для жизненного цикла экземпляра [IPresentation](../../com.aspose.slides/ipresentation).

## Методы

| Метод | Описание |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока в течение срока жизни экземпляра. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока в течение срока жизни экземпляра. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Это свойство определяет, могут ли создаваться временные файлы при работе с BLOB, что существенно уменьшает потребление памяти, но требует разрешения на создание файлов. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Это свойство определяет, могут ли создаваться временные файлы при работе с BLOB, что существенно уменьшает потребление памяти, но требует разрешения на создание файлов. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Корневой путь, где будут создаваться временные файлы. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Корневой путь, где будут создаваться временные файлы. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Определяет максимальный общий размер (в байтах), который могут занимать все BLOB в памяти. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Определяет максимальный общий размер (в байтах), который могут занимать все BLOB в памяти. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока в течение срока жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает улучшить потребление памяти и производительность при работе с BLOB, но источник (поток или файл) не может быть изменён в течение срока жизни экземпляра Presentation. Это пример:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Будет выброшено IOException, потому что pres.pptx заблокирован на время жизни Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // после освобождения объекта Presentation файл разблокируется и может быть удалён
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Возвращает:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока в течение срока жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает улучшить потребление памяти и производительность при работе с BLOB, но источник (поток или файл) не может быть изменён в течение срока жизни экземпляра Presentation. Это пример:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Будет выброшено IOException, потому что pres.pptx заблокирован на время жизни Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // после освобождения объекта Presentation файл разблокируется и может быть удалён
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Это свойство определяет, могут ли создаваться временные файлы при работе с BLOB, что существенно уменьшает потребление памяти, но требует разрешения на создание файлов.

--------------------

Все файлы будут удалены после завершения работы с презентацией.

**Возвращает:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Это свойство определяет, могут ли создаваться временные файлы при работе с BLOB, что существенно уменьшает потребление памяти, но требует разрешения на создание файлов.

--------------------

Все файлы будут удалены после завершения работы с презентацией.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Корневой путь, где будут создаваться временные файлы. По умолчанию будет использоваться системный временный каталог. Процесс-хост должен иметь разрешения на создание файлов и папок в этом месте.

**Возвращает:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Корневой путь, где будут создаваться временные файлы. По умолчанию будет использоваться системный временный каталог. Процесс-хост должен иметь разрешения на создание файлов и папок в этом месте.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Определяет максимальный общий размер (в байтах), который могут занимать все BLOB в памяти. По умолчанию все BLOB загружаются в память; только после достижения этого предела используются альтернативные механизмы (например, временные файлы). Хранение BLOB в памяти максимально повышает производительность, но может привести к высокому использованию памяти. Используйте это свойство, чтобы адаптировать поведение под вашу среду или требования.

--------------------

Это свойство игнорируется, если \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) установлено в false, поскольку тогда единственным доступным местом хранения является память, и ограничение использования BLOB в памяти не оказывает эффекта.

--------------------

Значение по умолчанию — 629 145 600 байт (600 МБ).

--------------------

Вы можете установить это свойство в ноль, но всё равно будет зарезервирован небольшой минимальный объём памяти.

**Возвращает:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Определяет максимальный общий размер (в байтах), который могут занимать все BLOB в памяти. По умолчанию все BLOB загружаются в память; только после достижения этого предела используются альтернативные механизмы (например, временные файлы). Хранение BLOB в памяти максимально повышает производительность, но может привести к высокому использованию памяти. Используйте это свойство, чтобы адаптировать поведение под вашу среду или требования.

--------------------

Это свойство игнорируется, если \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) установлено в false, поскольку тогда единственным доступным местом хранения является память, и ограничение использования BLOB в памяти не оказывает эффекта.

--------------------

Значение по умолчанию — 629 145 600 байт (600 МБ).

--------------------

Вы можете установить это свойство в ноль, но всё равно будет зарезервирован небольшой минимальный объём памяти.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |