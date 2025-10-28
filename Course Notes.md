# Cloud Computing Foundations


### Effective Technical Project Management
- Quarterly planning 
- Weekly Demo
- DevOps (Deploy your work always)
- Automated Testing
- Avoid Hero-Driven Development (keep up weekly deadline)
- Breaking down tasks into manageable time frames (4 hours to 3 days)

***Implement Effective Technical Project Management steps to your Educational Game Project***

**Progress Tracking with Trello (Trello - simple tracking tool for organizations)**
- Use 3 columns: To Do, In Progress, Done (aids the organization to know what is happening, saves time - cuts extra meetings). 

**Project Management Anti-Patterns**
- Hero-Driver Development (Causes self burn out, leads to unstable employment in organization)
- Crisis Driven Development (tackle the issue before moving on)

----

### AWS Cloud Development

**Continuous Integration** - CI tools automatically run tests whenever changes are pushed. This ensures that issues are caught early, making it easier to fix bugs.
Positive aspects of CI:
- Automated Testing
- Faster development cycle
- Reduced Integration Problems
- Improved Collaboration

**Unit Test** is a built-in testing framework for testing individual units or components of software (functions, methods) to ensure they work as expected.

**MakeFile** is a special file used to control the build process of a software project. It defines a set of rules that specify how to build different parts of a project and how to link them together.
```
# Makefile  

# Example Makefile recipe

lint:
	pylint **/*.py

test:  
	pytest -vv 
	
format:
	black *.py
	
clean:
	rm -rf build
	
# Call with `make lint` etc
```


**AWS Cloud9** is a cloud-based integrated development environment that allows developers to write, run, and debug their code from anywhere just a web browser.



### Python Project Scaffold (on AWS, Azure, Google Cloud)
```
**GitHub Repo Checkout**(Key Components)
├── Makefile
├── requirements.txt
├── hello.py
├── test_hello.py
└── virtualenv/
```

### Testing
**Types of Testing**
- Unit: testing individual pieces of code (one function or method)
- Integration: testing how different units work together (making sure combined parts interact correctly)
- Functional: testing a specific feature or function from the user's perspective
- End-to-End: testing the entire workflow from start to finish (like real user)
- Acceptance: testing to confirm the system meets business requirements and is ready for release
- Performance (Load Testing): testing how the system behaves under stress or heavy usage
- Exploratory: testing without a strict plan (testers explore the app freely to find unexpected bugs)

**Testing Strategy**
- Just Right (avoid excessive testing)
- Use judgement (use personal judgement to uncover what could be wrong)
- Save you time
- Automation (automate the testing with an environment that checks workability updated code)

