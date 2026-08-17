---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
url: /ru/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Binary Large Object (BLOB) — это бинарные данные, хранящиеся как единый объект — то есть BLOB может представлять аудио, видео или саму презентацию. Для оптимизации потребления памяти при работе с BLOB используют ряд техник — будь то уже сохранённые в презентации BLOB или добавляемые позже программно. С помощью [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) вы можете изменить различные аспекты поведения при работе с BLOB в течение срока жизни экземпляра [IPresentation](../../com.aspose.slides/ipresentation).

## Методы

| Методу | Описание |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока — в течение срока его существования. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока — в течение срока его существования. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Это свойство определяет, могут ли при работе с BLOB создаваться временные файлы, что значительно снижает потребление памяти, но требует разрешения на создание файлов. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Это свойство определяет, могут ли при работе с BLOB создаваться временные файлы, что значительно снижает потребление памяти, но требует разрешения на создание файлов. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Корневой путь, где будут создаваться временные файлы. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Корневой путь, где будут создаваться временные файлы. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока — в течение срока его существования. Если экземпляр является владельцем, он блокирует источник. Это помогает улучшить потребление памяти и производительность при работе с BLOB, однако источник (поток или файл) не может быть изменён в течение срока жизни экземпляра Presentation. Вот пример:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException будет выброшено, потому что pres.pptx заблокирован на время жизни Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // после того как объект Presentation освобожден, файл разблокируется и может быть удалён
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Возвращаемое значение:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока — в течение срока его существования. Если экземпляр является владельцем, он блокирует источник. Это помогает улучшить потребление памяти и производительность при работе с BLOB, однако источник (поток или файл) не может быть изменён в течение срока жизни экземпляра Presentation. Вот пример:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException будет выброшено, потому что pres.pptx заблокирован на время жизни Presentation
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

Это свойство определяет, могут ли при работе с BLOB создаваться временные файлы, что значительно снижает потребление памяти, но требует разрешения на создание файлов.

--------------------

Все файлы будут удалены после завершения работы с презентацией.

**Возвращаемое значение:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Это свойство определяет, могут ли при работе с BLOB создаваться временные файлы, что значительно снижает потребление памяти, но требует разрешения на создание файлов.

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

Корневой путь, где будут создаваться временные файлы. По умолчанию используется системный временный каталог. Процесс-хост должен иметь права на создание файлов и папок в этом месте.

**Возвращаемое значение:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Корневой путь, где будут создаваться временные файлы. По умолчанию используется системный временный каталог. Процесс-хост должен иметь права на создание файлов и папок в этом месте.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. По умолчанию все BLOB загружаются в память; только когда достигается этот предел, применяются альтернативные механизмы (например, временные файлы). Хранение BLOB в памяти обеспечивает максимальную производительность, но может привести к большому потреблению памяти. Используйте это свойство, чтобы настроить поведение под вашу среду или требования.

--------------------

Это свойство игнорируется, если \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) установлено в false, поскольку в этом случае память является единственным местом хранения, и ограничение использования BLOB в памяти не имеет эффекта.

--------------------

Значение по умолчанию — 629 145 600 байт (600 МБ).

--------------------

Вы можете установить это свойство в ноль, но всё равно будет зарезервировано небольшое минимальное количество памяти.

**Возвращаемое значение:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. По умолчанию все BLOB загружаются в память; только когда достигается этот предел, применяются альтернативные механизмы (например, временные файлы). Хранение BLOB в памяти обеспечивает максимальную производительность, но может привести к большому потреблению памяти. Используйте это свойство, чтобы настроить поведение под вашу среду или требования.

--------------------

Это свойство игнорируется, если \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) установлено в false, поскольку в этом случае память является единственным местом хранения, и ограничение использования BLOB в памяти не имеет эффекта.

--------------------

Значение по умолчанию — 629 145 600 байт (600 МБ).

--------------------

Вы можете установить это свойство в ноль, но всё равно будет зарезервировано небольшое минимальное количество памяти.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |