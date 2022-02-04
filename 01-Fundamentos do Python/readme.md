# Fundamentos do _Python_

## Fundamentos de Lógica de Programação

### Tipo Inteiro - _int_

* Em _Python_ tudo é objeto

Função do _Python_ que retorna o tipo de um objeto:
```python
type(1) # output: int
```

Algumas operações com números inteiros além das operações matemáticas basicas:

```python
100/9 # output: 11.11111111111111
```
Note que para essa operação com números inteiros, temos um resultado do tipo _float_, se quiser apenas a parte inteira do resultado, podemos usar:

```python
100//9 # output: 11
```
Note também, que mesmo uma divisão de inteiros, com resto zero, em _Python_ temos um _float_

```python
type(100/10) # output: <class 'float'>
```

```python
type(100/10) # output: <class 'int'>
```

Para usar exponenciação em _Python_:

```python
2**3 # output: 8
```

Outra observação sobre inteiros em _Python_ é que eles não tem uma limitação para sua representação, como exemplo em _Java_, onde o maior número inteiro é `2^63 - 1` do tipo _Long_. Já em _Python_ sua representação não tem um limite, desde que esse número caiba na memória.

```python
9999**9999 # output: 😲
```

Outra forma de representar um número muito grande, é usando o `_` como separador de milhar.

```python
1_234_567_891_012_345 # output: 1234567891012345
```
```python
type(1_234_567_891_012_345) # output: <class 'int'>
```

### Tipo Ponto Flutuante - _float_