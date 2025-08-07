# Exploring Java String Methods

## Cadet Name: Rafael Nico T. Maniquiz

-----

## Exercise 1: length() - Finding the String's Size

**Code Snippet:**

```java
public class StringLab {
    public static void main(String[] args) {
        String greeting = "Hello, Cadets!";
        int length = greeting.length();
        System.out.println("The length of the string is: " + length);
    }
}
```

**1. Prediction:**

```
The length of the string is: 14
```

**2. Observation:**

<img src="https://github.com/rick-maniquiz/Exploring-Java-String-Methods/blob/6b9e92cca30b68a85e94ac2782c7c3bd687eaae3/screenshots/1.png"/>


-----

## Exercise 2: charAt() - Accessing a Character

**Code Snippet:**

```java
public class StringLab {
    public static void main(String[] args) {
        String message = "Keep learning!";
        char character = message.charAt(5);
        System.out.println("The character at index 5 is: " + character);
    }
}
```

**1. Prediction:**

```
The character at index 5 is: l
```

**2. Observation:**

<img src="https://github.com/rick-maniquiz/Exploring-Java-String-Methods/blob/6b9e92cca30b68a85e94ac2782c7c3bd687eaae3/screenshots/2.png"/>

-----

## Exercise 3: substring() - Extracting a Part of a String

**Code Snippet:**

```java
public class StringLab {
    public static void main(String[] args) {
        String statement = "Java is powerful.";
        String part = statement.substring(5, 7);
        System.out.println("The extracted substring is: " + part);
    }
}
```

**1. Prediction:**

```
The extracted substring is: is
```

**2. Observation:**

<img src="https://github.com/rick-maniquiz/Exploring-Java-String-Methods/blob/6b9e92cca30b68a85e94ac2782c7c3bd687eaae3/screenshots/3.png"/>

-----

## Exercise 4: toUpperCase() and toLowerCase() - Changing Case

**Code Snippet:**

```java
public class StringLab {
    public static void main(String[] args) {
        String mixedCase = "This Is A Test";
        String upper = mixedCase.toUpperCase();
        String lower = mixedCase.toLowerCase();
        System.out.println("Uppercase: " + upper);
        System.out.println("Lowercase: " + lower);
    }
}
```

**1. Prediction:**

```
Uppercase: THIS IS A TEST
Lowercase: this is a test
```

**2. Observation:**

<img src="https://github.com/rick-maniquiz/Exploring-Java-String-Methods/blob/6b9e92cca30b68a85e94ac2782c7c3bd687eaae3/screenshots/4.png"/>

-----

## Exercise 5: indexOf() - Finding a Character or Substring

**Code Snippet:**

```java
public class StringLab {
    public static void main(String[] args) {
        String sentence = "The quick brown fox jumps over the lazy dog.";
        int indexOfFox = sentence.indexOf("fox");
        int indexOfZ = sentence.indexOf('z');
        int indexOfCat = sentence.indexOf("cat");
        System.out.println("Index of 'fox': " + indexOfFox);
        System.out.println("Index of 'z': " + indexOfZ);
        System.out.println("Index of 'cat': " + indexOfCat);
    }
}
```

**1. Prediction:**

```
Index of 'fox': 16
Index of 'z': 37
Index of 'cat': -1
```

**2. Observation:**

<img src="https://github.com/rick-maniquiz/Exploring-Java-String-Methods/blob/6b9e92cca30b68a85e94ac2782c7c3bd687eaae3/screenshots/5.png"/>

-----

## Exercise 6: equals() vs. equalsIgnoreCase() - Comparing Strings

**Code Snippet:**

```java
public class StringLab {
    public static void main(String[] args) {
        String str1 = "Java";
        String str2 = "java";
        String str3 = "Java";

        boolean isEqual1 = str1.equals(str2);
        boolean isEqual2 = str1.equals(str3);
        boolean isEqualIgnoreCase = str1.equalsIgnoreCase(str2);

        System.out.println("\"Java\".equals(\"java\"): " + isEqual1);
        System.out.println("\"Java\".equals(\"Java\"): " + isEqual2);
        System.out.println("\"Java\".equalsIgnoreCase(\"java\"): " + isEqualIgnoreCase);
    }
}
```

**1. Prediction:**

```
"Java".equals("java"): false
"Java".equals("Java"): true
"Java".equalsIgnoreCase("java"): true
```

**2. Observation:**

<img src="https://github.com/rick-maniquiz/Exploring-Java-String-Methods/blob/6b9e92cca30b68a85e94ac2782c7c3bd687eaae3/screenshots/6.png"/>

-----

## Exercise 7: replace() - Replacing Characters

**Code Snippet:**

```java
public class StringLab {
    public static void main(String[] args) {
        String original = "I like cats. Cats are cute.";
        String replaced = original.replace("cats", "dogs");
        System.out.println("Original: " + original);
        System.out.println("Replaced: " + replaced);
    }
}
```

**1. Prediction:**

```
Original: I like cats. Cats are cute.
Replaced: I like dogs. Cats are cute.
```

-----

**2. Observation:**

<img src="https://github.com/rick-maniquiz/Exploring-Java-String-Methods/blob/6b9e92cca30b68a85e94ac2782c7c3bd687eaae3/screenshots/7.png"/>

-----

## Exercise 8: trim() - Removing Whitespace

**Code Snippet:**

```java
public class StringLab {
    public static void main(String[] args) {
        String padded = "   Lots of spaces   ";
        String trimmed = padded.trim();
        System.out.println("Padded string length: " + padded.length());
        System.out.println("Trimmed string: '" + trimmed + "'");
        System.out.println("Trimmed string length: " + trimmed.length());
    }
}
```

**1. Prediction:**

```
Padded string length: 20
Trimmed string: 'Lots of spaces'
Trimmed string length: 14

```

**2. Observation:**

<img src="https://github.com/rick-maniquiz/Exploring-Java-String-Methods/blob/6b9e92cca30b68a85e94ac2782c7c3bd687eaae3/screenshots/8.png"/>
