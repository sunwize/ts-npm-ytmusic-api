# searchPlaylists

See the [guide](../../guides/usage/searchPlaylists.html) for information on how to use this.

## Properties

| Name    | Data Type | Description  |
| :------ | :-------- | :----------- |
| `query` | `string`  | Search query |

## Returns

`Promise<`[PlaylistDetailed](../interfaces/PlaylistDetailed.html)`[]>`

## TypeScript Source Code

```ts
public async searchPlaylists(query: string): Promise<PlaylistDetailed[]>
```
