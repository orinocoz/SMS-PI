To Send a SMS via the Command Line:
------------------
Example Below

With out flash
----

```
curl --data "to=077123456789&message=YOUR MESSAGE&hash=ENTERYOURHASH" http://www.smspi.co.uk/api/

```

with flash
---
```
curl --data "to=077123456789&message=YOUR MESSAGE&hash=ENTERYOURHASH&flash=yes" http://www.smspi.co.uk/api/

```


This can be thrown in to a bash

