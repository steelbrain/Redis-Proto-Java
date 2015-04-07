Redis-Proto-Java
==========
A super-lightweight Redis Protocol Encoder and Decoder in Java.

#### Usage

```js
System.out.println(
  RedisProto.Decode(
    RedisProto.Encode(
      new String[]{"SET", "KEY", "VALUE"}
    )
  ).length
);
// Outputs to 3
```

#### License
This project is licensed under the terms of MIT License.
