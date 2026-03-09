<!--
# [![Vinicius Silva](https://github.com/viniciusfdasilva/viniciusfdasilva/blob/main/icon/logo.png)](https://github.com/viniciusfdasilva/viniciusfdasilva/blob/main/icon/logo.png)
-->
## Hi 👋 I'm Vinicius Silva! :nerd_face:

For detailed information, please visit my [website](https://viniciusfdasilva.github.io/)

```C++
class AcademicLife {
public:
    Person person;
    string program;
    string university;
    string position;
    string location;
    string reseach_area;
    bool finished;

    AcademicLife(Person p,string program,string university,string position,string location,string area,bool finished) {
        this->person       = p;
        this->program      = program;
        this->university   = university;
        this->position     = position;
        this->location     = location;
        this->reseach_area = area;
        this->finished     = finished
    }
};

class Person {
public:
    std::string name;
    int age;

    Person(std::string name, int age) {
        this->name = name;
        this->age = age;
    }
};

Person* p = new Person("Vinicius Francisco da Silva", 27);

new AcademicLife(p,"Master's in Computer Science","PUCC MINAS","Undergraduate Student","ICEI","Computer Science",true);
new AcademicLife(p,"Postgraduate Latu Sensu","UNICAMP","Latu Sensu Student","Extecamp","Data Science",false);
new AcademicLife(p,"Master's in Computer Science","UFMG","Graduate Researcher","Compilers Lab","Compilers",false);
```
