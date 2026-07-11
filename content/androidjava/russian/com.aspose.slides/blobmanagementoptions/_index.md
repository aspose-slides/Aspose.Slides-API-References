---
title: BlobManagementOptions
second_title: Справочник API Aspose.Slides для Android через Java
description: Представляет параметры, которые могут использоваться для управления правилами обработки BLOB и другими настройками BLOB.
type: docs
url: /ru/com.aspose.slides/blobmanagementoptions/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Представляет параметры, которые могут использоваться для управления правилами обработки BLOB и другими настройками BLOB.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Создаёт новые параметры управления BLOB по умолчанию. |

## Методы

| Метод | Описание |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока в течение срока жизни экземпляра. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока в течение срока жизни экземпляра. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Это свойство определяет, могут ли создаваться временные файлы при работе с BLOB, что значительно снижает потребление памяти, но требует разрешения на создание файлов. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Это свойство определяет, могут ли создаваться временные файлы при работе с BLOB, что значительно снижает потребление памяти, но требует разрешения на создание файлов. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Корневой путь, где будут создаваться временные файлы. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Корневой путь, где будут создаваться временные файлы. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Создаёт новые параметры управления BLOB по умолчанию.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока в течение срока жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает улучшить потребление памяти и производительность при работе с BLOB, но источник (поток или файл) нельзя изменять в течение срока жизни экземпляра Presentation.

**Возвращаемое значение:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Это свойство определяет, может ли экземпляр класса Presentation быть владельцем источника — файла или потока в течение срока жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает улучшить потребление памяти и производительность при работе с BLOB, но источник (поток или файл) нельзя изменять в течение срока жизни экземпляра Presentation.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Это свойство определяет, могут ли создаваться временные файлы при работе с BLOB, что значительно снижает потребление памяти, но требует разрешения на создание файлов.

--------------------

Все файлы будут удалены после завершения работы с презентацией.

**Возвращаемое значение:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Это свойство определяет, могут ли создаваться временные файлы при работе с BLOB, что значительно снижает потребление памяти, но требует разрешения на создание файлов.

--------------------

Все файлы будут удалены после завершения работы с презентацией.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Корневой путь, где будут создаваться временные файлы. По умолчанию будет использоваться системный временный каталог. Процесс-хостинг должен иметь разрешения на создание файлов и папок в этом месте.

**Возвращаемое значение:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Корневой путь, где будут создаваться временные файлы. По умолчанию будет использоваться системный временный каталог. Процесс-хостинг должен иметь разрешения на создание файлов и папок в этом месте.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. По умолчанию все BLOB загружаются в память; только при достижении этого предела используются альтернативные механизмы (например, временные файлы). Сохранение BLOB в памяти максимизирует производительность, но может привести к большому использованию памяти. Используйте это свойство, чтобы адаптировать поведение к вашей среде или требованиям.

--------------------

Это свойство игнорируется, если \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) установлено в false, поскольку в этом случае память является единственным доступным местом хранения, и ограничение использования BLOB в памяти не имеет эффекта.

--------------------

Значение по умолчанию — 629 145 600 байт (600 МБ).

--------------------

Вы можете установить это свойство в ноль, но небольшое минимальное количество памяти всё равно будет зарезервировано.

**Возвращаемое значение:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. По умолчанию все BLOB загружаются в память; только при достижении этого предела используются альтернативные механизмы (например, временные файлы). Сохранение BLOB в памяти максимизирует производительность, но может привести к большому использованию памяти. Используйте это свойство, чтобы адаптировать поведение к вашей среде или требованиям.

--------------------

Это свойство игнорируется, если \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) установлено в false, поскольку в этом случае память является единственным доступным местом хранения, и ограничение использования BLOB в памяти не имеет эффекта.

--------------------

Значение по умолчанию — 629 145 600 байт (600 МБ).

--------------------

Вы можете установить это свойство в ноль, но небольшое минимальное количество памяти всё равно будет зарезервировано.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |