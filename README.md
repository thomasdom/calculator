# Calculator

Calculator is an application which perform simple mathematical operations on numbers.

This project is solely used to integrate Apache Maven with GitHub Actions.

## Installation

Use the [Apache Maven](https://maven.apache.org/)'s goal `install` to install dependencies.

```shell
mvn install
```

## Usage

```java
import com.thomasdomingues.calculator.Operations;

class Application {
    public static void main(String[] args) {
        int threePlusFour = Operations.add(3, 4);

        System.out.println(threePlusFour);
    }
}
```

## Contributing

See [CONTRIBUTING.md](/CONTRIBUTING.md).

## License

[MIT](https://choosealicense.com/licenses/mit/)
