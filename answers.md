1. What is the difference between new and create for a model?

new makes an instance of the model in Ruby memory and lets us modify the variables of the model.
create makes a new model and saves it to the database directly with default values.

2. What command combined with new will emulate the same behavior as create?

Model.new.save is the equivalence of create.

3. What is the column that exists on every table but we did NOT define?

"created_at" and "updated_at"

4. What single line of ruby code can insert a cat with the name "hat" in the database?

Cat.new({name:"hat"}).save

5. What was the most confusing part over the last few weeks?

It is hard to find ruby documentation of basic syntax (like generate) online because there are a lot of ways to execute the same command. And there is no documentation similar to Java Docs (as far as I know).

6. How did you like this homework in comparison with the others?

It was a good homework.
