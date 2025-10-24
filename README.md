# The-solution-of-modelsim-linting-disappearing
When I try to put a large folder into the Vscode workplace,I met a problem.The linting function is disappearing,and then it never goes work even reload it.The solution is in the README file,hope to have some help for you.


reasons and the solution:
////////
1.When adding the big folders,the work library on your modelsim/questasim will create a _lock file,which stops the process of the linting.
the solution is simple,just delete the _lock file is ok.
////////
2.The conflict between your extension' setting modelsim>>lintting>>path and your envirment path,it isn't happen for someone,but for me,it happens.
the solution is deleting the modelsim>>linting>>path,just keep it blank.
