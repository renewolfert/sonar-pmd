
# EmptyWhileStmt
**Category:** `pmd`<br/>
**Rule Key:** `pmd:EmptyWhileStmt`<br/>
> :warning: This rule is **deprecated** in favour of [S00108](https://rules.sonarsource.com/java/RSPEC-00108).

-----

Empty While Statement finds all instances where a while statement does nothing. If it is a timing loop, then you should use Thread.sleep() for it; if it's a while loop that does a lot in the exit expression, rewrite it to make it clearer.

<p>
  This rule is deprecated, use {rule:squid:S00108} instead.
</p>
