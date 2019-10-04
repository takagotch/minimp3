### minimp3
---
https://github.com/tosone/minimp3

```go
// decode_test.go

func TestDecoder_CloseEarly2(t *testing.T) {
  var err error
  var file, pcmFile *os.File
  var dec *Decoder
  
  if file, err = os.Open("./example/test.mp3"); err != nil {
    t.Error(err)
  }
  if dec, err = NewDecoder(file); err != nil {}
}
```

```
```

```
```


