---
description: How to diagnose startup panics.
---

# Panics

## Overview

During system startup it is possible for an unrecoverable error to occur, know as a panic. Panics can come from many different sources and subsystems. Below you can find some information on how to handle basic and/or common system panics, however if you are experiencing a panic that isn't listed below, please visit the community forums.

## Invalid CmdLine

### Missing cmdline

```
Error: invalid-cmdline
Reason: 
```

{% hint style="danger" %}
 This error is caused by a corrupted filesystem.

If you have modified any files manually, you should revert them, otherwise a serious fault has occurred, such as a failing USB. You should backup your SkylarkOS configs and restore them to another USB.
{% endhint %}



