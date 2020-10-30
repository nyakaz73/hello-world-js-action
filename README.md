# hello-world-js-action
Hello World Javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage
```yml
uses: nyakaz73/hello-world-js-action@v1.1
with:
  who-to-greet: 'Your own name here'
```