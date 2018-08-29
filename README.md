# links

This repository contains links to pages (`pagesWithLinks()`) that have my stuff on them.

```c++
...

double readerInterest();

...

  std::string pagesWithLinks()
  {
    std::string pgs{"that may contain links to pages"};
    while (readerInterest() > 0.0)
    {
      pgs.append(" that may contain links to pages");
      readerInteres = readerInteres - 1.0;
    }
    return pgs;
  }

...
```

## Getting Started

You don't have to have a look at the README file first.

Wait...

Uh...

### Prerequisites

A link you're looking for.

```c++
#include<one_of_sams_links>
```

### Finding

Look for the thing in the list of things and go to it.

```c++
int linkCount();
randomlib::link samLinks[linkCount()];
randomlib::link aLink();
int initSamLinks();
int goToSamLink(lineNum);

...

int lookWithYourEyesFor(randomlib::link myLink)
{
    for (int lineNum = 0;lineNum < linkCount();lineNum++)
    {
      if (samLinks[lineNum] == myLink)
      {
          return lineNum;
      }
    } 
}

...

  initSamLinks();

...

  goToSamLink(lookWithYourEyesFor(aLink());

```

## Built With

* [GitHub](https://github.com/) - A website you've probably never heard of
* [Computer](https://www.microsoft.com/en-us/windows/view-all-devices) - The only kind of machine you should be using for this kind of thing
* [Intelligence](https://bulbapedia.bulbagarden.net/wiki/Bidoof_(Pok%C3%A9mon)) Imperative to creating content of this quality

## Authors

* **Samuel Bondoc:** *Everything that makes this bad* - [sBondoc](https://github.com/sBondoc)

## Acknowledgments

* I have no idea what I'm doing
