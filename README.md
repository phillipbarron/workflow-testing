# Testing workflow 

Test repo to test workflow behaviour / tag caching / triggers

Ideally, we want to trigger a check when a label is add, which could be after the initial PR. There appears to be some caching behaviour which happens at PR creation time which means that when a label is added, a condition in the workflow that evaluates the tags for a PR is based on the earlier state.

