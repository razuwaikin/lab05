cmake_minimum_required(VERSION 2.8)
project(banking)
add_library(Account STATIC Account.h Account.cpp)
add_library(Transaction STATIC Transaction.cpp Transaction.h)
