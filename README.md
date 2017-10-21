# Intersystems_Caché
Code written in Intersystems Caché; code, similar to MUMPS, to be used to make administration of a Caché database easier. 

## Getting Started
* Have a Caché environment installed and properly configured.
* Make use of Caché Studio to edit and commit Caché code.

### Prerequisites
* Install [Caché](https://www.intersystems.com/products/cache/) - database that powers transaction processing applications
* Install [Caché Studio](https://download.intersystems.com/download/login.csp) - 
![Caché Studio img](http://docs.intersystems.com/latest/csp/docbook/images/gstd_studiodiagram.png)

### Installing
Via Caché Studio:
1. Create new routine in the namespace you would like to run it in
2. Copy code into your new routine
3. Save the routine
4. Compile routine

## Running the tests
Goto the namespace where you compiled the routine, and run the script:
* ```DO ^%SecurityCopy``` - Will prompt you to use either Export or Import tags
* ```DO Export^%SecurityCopy``` - Will run export portion
* ```DO Import^%SecurityCopy``` - Will run import portion

## Authors
* **Mike Northrop** - *Design, Development*
