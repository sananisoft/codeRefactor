please do not use $data = $request->all() and then $data['propertyName'] so don't assign to to variable 
don't use this type instead of use $request->propertyName direct use in if condition or in any logic in code.

Dont use model::all() it will stuck at somewhere due to in case of million of records use job::dispatch or paginate 

and dont use db::(table) instead of use relationship data because we are not using core php here 


and over all code is ok not too much because of too many if else and foreach loops 
to avoid using foreach loops and where necessary then use other wise use collections methods instead of foreach loop.

thanks:)
