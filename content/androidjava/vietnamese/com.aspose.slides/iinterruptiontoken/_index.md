---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
url: /vi/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Lớp này đại diện cho token được sử dụng để báo hiệu cho các tác vụ chạy lâu liệu đã có yêu cầu ngắt hay chưa.
## Phương thức

| Phương thức | Mô tả |
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