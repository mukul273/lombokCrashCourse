This is a crash course on lombok library being used in Spring boot.

Lombok is used to avoid lot of boiler plate code when it comes writing getters and setters for a bean.

This project uses web, jpa, h2 and lombok libraries.

@Getter and @Setter can be used at field level as well as class level

if we have final variable in the class then @NoArgConstructor can't be used

@Value annotation makes the fields private and final. So the class becomes immutable. No setters.
@Value precedes over @Data. 

@Builder will build the object for class.

@NonNull will make sure that object is not null checked. No more nullpointerexception

@Log4J or similar annotations will bring in the logger mechanism. No more instantiation of logger in the class.

Please refer https://projectlombok.org/features/all

