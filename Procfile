user: hypercorn user --reload --debug --bind user.local.gd:$PORT --access-logfile - --error-logfile - --log-level DEBUG
# leaderboard: hypercorn leaderboard --reload --debug --bind leaderboard.local.gd:$PORT --access-logfile - --error-logfile - --log-level DEBUG

primary: ./bin/litefs -config ./etc/primary.yml
secondary1: ./bin/litefs -config ./etc/secondary1.yml
secondary2: ./bin/litefs -config ./etc/secondary2.yml

# game: hypercorn game --reload --debug --bind game.local.gd:$PORT --access-logfile - --error-logfile - --log-level DEBUG