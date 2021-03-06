SOLID:

[S] - Single Responsibility Principle (Princípio da Responsabilidade Única SRP)

    Nunca deve haver mais de um motivo para uma classe mudar.
    No exemplo de código desenvolvido, podemos reparar que a classe Client tem apenas métodos da sua Responsabilidade (CRUD) e a ação
    de enviar email está noutra classe (Notify), desta forma garantimos que cada classe tem apenas uma responsabilidade, o que facilita o uso e a manutenção.

----

[O] - Open/Closed Principle (Princípio Aberto/Fechado OCP)

    Aberto para extensão e Fechado para modificação.
    Mudar código pode ser perigoso, pois pode alterar o comportamento da classe de forma errada.
    No nosso exemplo temos a classe Car que implementa a interface IVehicleCar, e é lá que podemos fazer as alterações que necessitamos para implementar a classe     Car.

----

[L] - Liskov Substitution Principle (Princípio da Substituição de Liskov LSP)

    Uma classe derivada pode ser substituível por sua classe base.
    Classe abstrata -> obriga a que as classes extendem da mesma. É a base das classes. 
    Neste caso o cliente ou paga com cartão de débito ou de crédito, mas a base é o NuBank.
    A abstração é boa, para a escalabilidade do projeto.

----

[I] - Interface Segregation Principle (Princípio da Segregação de Interfaces ISP)

    Classes não devem ser forçadas a depender de métodos que não usam.
    Princípio que separa as nossas interfaces.

----

[D] - Dependency Inversion Principle (Princípio da Inversão de Dependência DIP)

    Módulos de alto nível não devem depender de módulos de baixo nível. 
    Ambos devem depender de abstrações; Abstrações não devem depender de detalhes.


Reference: https://www.udemy.com/course/curso-design-patterns-typescript/
