# Overview

# Usage

Just use confirm inbetween two pipes and away you go:

```
ls | confirm | xargs rm
```

You we be asked to confirm each file, and only the confirmed ones are passed onto the next command.

Too easy!
