---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: Lớp này đại diện cho token được sử dụng để báo hiệu cho các tác vụ chạy lâu liệu có yêu cầu ngắt hay không.
type: docs
url: /vi/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Lớp này đại diện cho token được sử dụng để báo hiệu cho các tác vụ chạy lâu liệu có yêu cầu ngắt hay không.
## Methods

| Method | Description |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Trả về true nếu đã yêu cầu ngắt. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Ném một ngoại lệ nếu đã yêu cầu ngắt. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Trả về true nếu đã yêu cầu ngắt.

**Trả về:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Ném một ngoại lệ nếu đã yêu cầu ngắt.