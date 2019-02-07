# Old 6.004 Labs

To use Jade or BSim locally in standalone mode, simply run

    python server.py

to start a basic HTTP server listening on port localhost:8000.
server.py is compatible with both Python 2.7+ and 3.6+.
You can access the tools at

    http://localhost:8000/index.html

and click on the link to access that Lab's Jade or BSim tool.

In the standalone version of the tools, changes are saved to the local
server as they're made.  The saved state is for the particular .html
file you accessed, so if you have several .html files for, say,
different projects, their state will be stored separately.  Next time
you browse to the URL above, you'll be able to pick up your design
where you left off.
