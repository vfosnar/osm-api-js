# getOwnUserBlocks

```ts
import { getOwnUserBlocks } from "osm-api";

await getOwnUserBlocks();
```

Response:

```json
[
  {
    "created_at": "2014-10-07T09:21:12Z",
    "ends_at": "2014-10-07T09:21:31Z",
    "id": 1,
    "needs_view": false,
    "reason": "test block",
    "creator": { "uid": 632, "user": "pnorman" },
    "revoker": { "uid": 632, "user": "pnorman" },
    "user": { "uid": 1154, "user": "SimonDev" },
    "updated_at": "2014-10-07T09:21:31Z"
  }
]
```
