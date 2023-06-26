# abcde
```
module qy(A, B, C, D, E, F);
  input A, B, C, D, E;
  output F;
  
  assign F = (~A & ~B& ~E) | (A & C & E) |(B &~D&E);
endmodule
```
