# Sarah Barron 
## Waterford Institute of Technology
## HDip Computer Science
### Module: Computer Systems
### Assignment 1: Design a company directory, using Shell Programming
### Result: 91%


#### Assignment Background

This assignment requires a Linux-based software tool to allow a local company to keep track of all of its
business contacts.

The owner is particularly interested in keeping track of each business name, contact
person’s full name, address, mobile number, and email address.

Based upon the above information the owner would like to be able to search for particular
business entries, add new business contacts and remove old contacts from their own
system.

This tool should also provide the user with the ability to e-mail (1) any and (2) all of the
contacts listed in the address book with details of upcoming sales or discount offers etc.

#### Assignment Details

Develop a "menu driven" shell program that will allow the user to interactively update (i.e.
add, remove), search and list all their business contacts information, which is stored locally
in a file called BusinessDetails and email the business.

The format of the "BusinessDetails" file should take the following format:
<Company Name> <Contact First and Last Name> <Postal Address> <Contact
phone Number> <Email Address>

#### Guidelines

The following shell-programming assignment comprises of 4 separate functional
components (separate shell programs).

1. The first script called AddBiz, should be a standalone script that will update the
Address Book file with details of a new business
This script should take five command line arguments, as shown in Figure 1 above
2. The second script called RmBiz should remove all of a business’s information from
the "AddressBook" based on a particular businesses name or contact name.
3. The third script should allow the user to search for an existing business based upon
any of that businesses information. Call this script FindBiz.
4. The final and most important part of this assignment is to develop a script called
Menu.

This script will present the user with a command line menu. 

This menu will allow the user to select from any of the previously mentioned shell scripts
(i.e. AddBiz, RmBiz and FindBiz) and a fourth feature which will allow the user
to e-mail any or all the companies listed in the Address Book.

You should also consider:
- Descriptive use of commenting in your files
- Good use of spacing and indentation in your files
- Clear, attractive and easy to follow output to the user
- Correct use of exit status
- Error checking: duplication of listings – is this OK or not? valid user menu choice;
valid email address; is a user allowed enter blanks? if any details are duplicate in the
address book, how can this be presented to the user to filter? Are search terms case
insensitive?
- Can a user return to the main menu from any point?

#### Result - 91%

I completed all of the functionality asked for in the assignment specification using the following tools and technologies:
- Oracle VM VirtualBox - VirtualBox allows additional operating systems to be installed on it, as a Guest OS, and run in a virtual environment.
- Ubuntu 19.04 - Linux Operating System
- Shell Scripting - writing a series of command for the shell to execute
- Grep - A pattern search tool.
- Sed - A stream editor, able to search for a pattern and apply the given transformations and/or commands.
- AWK - A loosely typed programming language for stream processing to matched, substituted and worked around strings 

